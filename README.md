#  Smart Object Recognition using HuskyLens

## 1.  Project Overview

This project demonstrates the use of the **HuskyLens AI Vision Sensor** to recognize real-world objects using built-in machine learning capabilities.  
In this prototype, the HuskyLens was trained to detect a **water bottle**, and once trained, it is able to recognize the object automatically and independently — without the need for a computer.
! [Husky](Husky2)

This project serves as a practical introduction to **Computer Vision** and **AI-based object detection**.

---

## 2.  What is HuskyLens?

**HuskyLens** is a smart AI camera developed by DFRobot. It supports multiple built-in recognition modes such as:

- Face Recognition  
- Object Recognition  
- Object Tracking  
- Color Detection  
- QR Code / AprilTag Reading  
- Line Tracking  

The device is beginner-friendly, programmable via its onboard buttons, and works in real time without requiring deep coding knowledge.

---

##  3. Hardware Components Used :

| Component           | Description                                  |
|---------------------|----------------------------------------------|
|  HuskyLens AI Camera| Main AI vision sensor for object recognition |
|  USB Type-C Cable   | For powering and programming the device      |
|  Jumper Wires       | For future integration with Arduino/ESP32    |
|  Power Bank         | Portable external power source               |

---

## 4.  How the Project Was Built :

1. **Powering the HuskyLens**
   - Connected to a power bank via USB Type-C.

2. **Entering Object Recognition Mode**
   - Selected "Object Recognition" from HuskyLens’ menu.

3. **Training on the Target Object**
   - Pointed the camera at a **water bottle**.
   - Pressed the "Learning" (◉) button to save the object as `ID-1`.

4. **Testing the System**
   - Once powered, the camera successfully recognized the water bottle and displayed the ID on its screen.

---

## 5.  Image of the Project Setup : 

> Below is an image showing the actual tools and setup used in this project:

![HuskyLens Project](assets/huskylens-demo.jpg)

*(Make sure to place the image inside a folder named `assets` and update the file name if needed)*

---

## 6.  Project Benefits : 

- Offline, real-time object recognition.
- Portable and easy to deploy using a power bank.
- Can be extended to trigger actions (e.g., alarms, motors, doors).
- A hands-on introduction to AI, vision systems, and machine learning concepts.

---

## 7.  Future Improvements :

-  Add a buzzer to alert when the object is detected.
-  Integrate with Arduino to control servos or electronic locks.
-  Connect with ESP32 to send alerts over Wi-Fi or log data.
-  Train HuskyLens on multiple objects for broader applications.

---

## 8.  Author :

- **Name**: *(Your name here)*
- **Role**: Developer / Student / Engineer
- **Purpose**: Personal Experiment / Academic Project / AI Demo

---

## 9.  License :

This project is licensed under the **MIT License**.  
Refer to the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgments

- [DFRobot Official HuskyLens Documentation](https://wiki.dfrobot.com/HUSKYLENS_V1.0_SKU_SEN0305)
- GitHub for providing project hosting and collaboration tools
- Open-source communities supporting beginner AI development
