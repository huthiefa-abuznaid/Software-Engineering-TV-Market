# Software-Engineering-TV-Market
An object-oriented software engineering blueprint for a TV retail shop system. Designed with UML modeling, a 3-tier architecture, and strict non-functional constraints for sales, delivery, and repairs.
# TV Shop System (Software Engineering Blueprint)

This repository contains the software analysis, requirements, and architectural design for a comprehensive **TV Shop System** developed for the *Software Engineering (COMP 334)* course at Birzeit University.

The project models a modern TV retail store carrying over **120 television models** from five major brands and approximately **60 types of accessories**. The system streamlines the business workflows across showroom sales, warehouse inventory management, customer deliveries, installations, and specialized repair requests.

---

## ⚙️ Core Business & System Workflows

The system covers the following primary use cases:
1. **Submit Repair Request:** Manages repair requests by evaluating strict policies and identifying warranty details from purchase receipt numbers.
2. **Place Order:** Handles showroom and digital customer orders for televisions and accessories.
3. **Delivery & Installation:** Coordinates a dedicated field team to deliver and mount units.
4. **Receive & Register New Stock:** Records newly arrived shipments and automatically generates low-stock alerts if item counts drop below thresholds.
5. **Damaged/Missing Item Auditing:** Flags specific units as compromised to update availability states in real time.

---

## 🏛️ Architectural Design & Goals

The system was designed following standard software engineering methodologies (utilizing a **Waterfall Model**) and modeled with UML. 

### System Design Choices
- **3-Tier Architecture:** Organizes the system into three decoupled layers:
  1. **UI / Boundary Layer** (Web Browser)
  2. **Middle / Controller Layer** (Web Server)
  3. **Infrastructure / Database Layer** (DB Server)
- **Low Coupling & High Cohesion:** Ensuring modules like Ordering & Payments remain isolated, while keeping cohesive packages like Inventory Management tightly organized.
- **Data Integrity and Constraints:** Prevent stock figures from dropping below zero and utilize audit logs to maintain data reliability.

---

## 👥 Group 11 Team Members
* **Hutheyfa Ammar** – Project Manager
* **Ramzi Fiqyat** – Secretary & Requirements Engineer
* **Anas Ghazawnah** – Programmer
* **Husam Atwan** – Technical Architect
* **Mohammad Foqahaa** – QA / Software Tester
