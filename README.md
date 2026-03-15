
# **AI-Powered Coastal Hazard Detection & Victim Tracking System**

An advanced maritime safety solution designed to mitigate risks in coastal recreation areas. This project leverages the state-of-the-art **YOLOv12** architecture to provide real-time monitoring, hazard alerts, and automated victim tracking for marine environments.

---

## **Overview**

Traditional coastal safety relies heavily on manual patrols, which are often limited by visibility and human resources. This system fills that gap by providing 24/7 automated surveillance, specifically targeting high-risk phenomena: **Rogue Waves (Crazy Flat Waves)** and **Rip Currents**.

By integrating professional maritime knowledge with deep learning, the system establishes a comprehensive safety mechanism from prevention to rescue.

## **Core Features**

* **Shoreline Pedestrian Detection**: Real-time monitoring of visitors on the beach to prevent entry into high-risk zones.
* **Rogue Wave (CFW) Alerting**: Immediate detection of sudden, large-scale wave threats.
* **Rip Current Identification**: Visual analysis of water patterns to identify dangerous seaward currents.
* **Victim Localization**: Automatic pinpointing of individuals in distress.
* **Dynamic Victim Tracking**: Continuous tracking of a victim's movement to assist rescue teams in high-stakes environments.

## **Technical Implementation**

This project is built upon the **YOLOv12** (You Only Look Once v12) framework, utilizing its superior attention mechanisms and high-speed inference capabilities to ensure accuracy even in complex, low-contrast marine conditions.

---

## **Getting Started**

### **Installation**

Ensure you have Python 3.9+ installed, then install the necessary dependencies:

```bash
pip install -r requirements.txt

```

### **Usage**

You can launch specific monitoring modules by running the following detection scripts:

#### **1. Rogue Wave (CFW) Detection & Alert**

To start real-time monitoring for rogue waves:

```bash
python detect_cfw_alert.py --source 0 --weights yolov12_cfw.pt

```

#### **2. Rip Current Detection & Alert**

To analyze coastal areas for rip current threats:

```bash
python detect_rip_alert.py --source video.mp4 --weights yolov12_rip.pt

```

---

## **System Workflow**

1. **Pre-warning**: Integration of meteorological data to assess hazard probability.
2. **Real-time Detection**: Computer vision identifies hazards as they occur.
3. **Post-disaster Tracking**: Locks onto victims to streamline rescue operations.

## **License**

This project is licensed under the **Apache License 2.0** - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

