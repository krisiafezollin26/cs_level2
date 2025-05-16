# cs_level2_forecast

This repository contains advanced forecasting scripts and files used for **Level 2 customer support tickets**. These cases require deeper analytical review, manual validation, or special handling that falls outside the scope of Level 1 automation.

---

## 🔍 What is Level 2 Forecasting?

Level 2 forecasting handles **escalated tickets** that cannot be resolved through the standard Level 1 cs. 

These tickets are typically flagged during Level 1 checks or submitted directly by strategy, planning, or analytics teams.

---

## 📂 Repository Structure

### `Rolling 52 wk main file`
Maintains the core 52-week rolling forecast. Used for high-level forecasting across all standard dimensions. Supports escalated adjustments and mid-cycle reforecasts.

### `Rolling 52 wk variants`
Handles variant-level breakdowns (e.g., product/channel/region). Required for escalations involving segmented forecasts or where aggregate trends diverge from underlying components.

### `Volume forecast files`
Stores both base and manually adjusted forecast volumes. These files reflect cases where standard seasonality or baseline logic does not explain observed or expected trends.

### `Seasonality extraction/baseline files`
Used for re-running or adjusting seasonality and baseline calculations.

### `Onboarding vol files`
Dedicated files for forecasting new volume entries. 
Requires manual inputs or strategic assumptions.


---

## ⚠️ Important Notes

- **Always double-check data sources**, especially Google Sheets IDs and Metabase connections.
- Avoid publishing updates to live dashboards unless reviewed and confirmed.
- Maintain clear documentation for all overrides, assumptions, and escalated changes.

---

## ✅ When to Use This Pipeline

Usually we runt the scripts every month to check cs level 2 volume.

---

Note: Always double-check the Google Sheets ID before running any notebook to ensure that you are working with the correct data.


