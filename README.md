# Kinect Body Tracking for Unity

A small Unity tool for **real-time body tracking using Microsoft Kinect**, which replicates the user's movements onto a **3D character model**.
It can be easily used for the Kinect game developing, any 3D model can be adapted.

The project is built in **Unity 2023.2** and uses a **custom Kinect SDK integration** based on the official Microsoft Kinect SDK, adapted and modified to work smoothly inside Unity and to drive a humanoid 3D model.

---

# Features

- Real-time **body tracking**
- Motion replication on a **3D humanoid model**
- Custom adaptation of the **Microsoft Kinect SDK**
- Example scenes demonstrating possible uses of the SDK

---

# Requirements

- **Unity 2023.2**
- **Microsoft Kinect sensor**
- **Kinect SDK for Windows**
- Windows PC compatible with Kinect

---

# Setup / How to Run

1. Clone or download this repository. (some paths should be fixed for meta's running on your own machine).

2. Open **Unity Hub**.

3. Open the project using **Unity 2023.2**.

4. Connect the **Kinect sensor** to your computer. (using the official adapter).

5. Open one of the demo scenes. (there is a demo of the 3D tracking with a model in the Assets folder in KinectScripts).

6. Press **Play** in the Unity editor.

If everything is configured correctly, the Kinect will start tracking the user and the **3D avatar will replicate the body movements in real time**.

---

# Project Structure

## `KDemos`

This folder contains **demo scenes and examples** showing possible uses of the Kinect SDK integration.

These demos demonstrate how to:

- Access Kinect body tracking data
- Apply the tracked motion to a 3D character
- Test the SDK functionality inside Unity

They can also serve as a **starting point for new projects** using the SDK.

---

## `KinectScripts`

This folder contains **all the core assets and scripts required for Kinect integration**.

It includes:

- Scripts for **body tracking**
- Kinect **data processing**
- Components used to **map the Kinect skeleton to the 3D model**

Part of this code is derived from the **official Microsoft Kinect SDK**, but it has been **modified and adapted** to:

- Work properly inside **Unity**
- Improve compatibility with **Unity's transform system**
- Enable **real-time control of the 3D model**