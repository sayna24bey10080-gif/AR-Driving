AR Driving (Unity AR Project)

An augmented reality driving game built in Unity. The user scans a flat surface
with their phone camera, places a virtual car on it, and drives the car around
to collect packages in the real world.

-Features
- Plane detection: finds floors and tables using AR Foundation
- Reticle placement: a reticle shows where the car will appear
- Car controls: drive the car around the detected surface
- Package spawning: packages appear on the surface for the car to collect
- Light estimation: the virtual car matches the lighting of the room

-Tech Stack
- Unity (version: add yours here, e.g. 2022.3 LTS)
- AR Foundation + ARCore XR Plugin
- C# scripts: CarBehaviour, CarManager, DrivingSurfaceManager,
  PackageSpawner, ReticleBehaviour, LightEstimation
- Target platform: Android

-How to Run
1. Clone the repository: `git clone https://github.com/sayna24bey10080-gif/AR-Driving.git`
2. Open the folder in Unity Hub and let it import the project.
3. Go to File > Build Settings and switch the platform to Android.
4. Connect an ARCore-supported Android phone with USB debugging on.
5. Click Build And Run.

-How to Play
1. Move your phone slowly to scan the floor or a table.
2. Tap when the reticle appears to place the car.
3. Drive the car and collect the packages.

<img width="500" height="704" alt="WhatsApp Image 2026-10-09 at 9 17 26 PM" src="https://github.com/user-attachments/assets/551011be-3c8f-49ee-ad72-c4ec135c76cc" />


-Author
Sayna Patel
