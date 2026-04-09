# Inventory-Control-Dashboard

##  The Objective
The goal of this analysis was to create a centralized system for tracking product movement (**Stock-In vs. Stock-Out**) and to provide actionable data for procurement. The dashboard ensures that high-demand items are replenished before reaching a zero-stock state, reducing the risk of lost sales and operational downtime.

##  Key Performance Indicators (KPIs)
* **Total Products Monitored:** 20
* **Total Stock Value:** $2,942.00
* **Current Inventory Level:** 431 Units
* **Reorder Rate:** 55% (11 out of 20 products require immediate replenishment)
* **Out-of-Stock Items:** 6 Products (30% of total catalog)

---

## Technical Features of the Dashboard

### 🟢 Automated Stock Alerts
The dashboard utilizes conditional logic that automatically triggers a **"YES"** reorder status when the quantity of a specific item falls below its predefined unit threshold.

### 🔗 Supplier Mapping
This feature links each "at-risk" product directly to the associated supplier's contact information. This facilitates rapid procurement and reduces the time spent navigating vendor databases during stock emergencies.

### 💰 Valuation Engine
A real-time calculation engine that determines the total stock value based on individual unit costs. This allows for an up-to-the-minute understanding of capital tied up in inventory.

---
