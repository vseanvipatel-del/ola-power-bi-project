# ola-power-bi-project
# 🚖 Ola Trips Operational Dashboard Analysis

A comprehensive Business Intelligence (BI) and Exploratory Data Analysis (EDA) project analyzing taxi/ride-sharing operational transactions. This project utilizes **Power BI** to construct interactive dashboards and data models, paired with a strategic presentation outlining performance bottlenecks, ride metrics, and driver-passenger dynamics.

## 📌 Project Overview
The objective of this analysis is to evaluate ride-sharing data to optimize trip completion rates, minimize operational drop-offs (cancellations), and understand geographic and temporal demand patterns. The project converts raw, complex operational transactional logs into clean, visual business metrics designed to support strategic decision-making for ride-sharing platforms.

---

## 📊 Core Business & Operational Metrics Tracked

The interactive dashboard focuses on tracking performance across several operational pillars:

### 📈 1. Ride Volume & Trip Status Dynamics
* **Total Bookings & Completion Rates:** Gauging the overall health of the platform by measuring successfully completed trips against total requests.
* **Cancellation Analysis:** Segregating drop-offs to pinpoint issues—distinguishing between passenger cancellations (e.g., long wait times) and driver rejections.
* **Incomplete & Dropped Rides:** Mapping out transactional losses to identify technical or operational friction points.

### 💰 2. Revenue & Financial Performance
* **Gross Transaction Value (GTV):** Aggregating total booking values across different time horizons, car categories, and regions.
* **Customer Spend vs. Driver Earnings:** Tracking platform commissions, standard fares, and additional surcharges.
* **Payment Method Mix:** Evaluating transaction distributions across Cash, Digital Wallets, and Credit/Debit cards to understand consumer payment behavior.

### 🚗 3. Fleet & Category Segmentation
* **Vehicle Class Demand:** Slicing ride metrics by product tiers (e.g., Ola Mini, Prime Sedan, Prime SUV, Auto, Bike) to evaluate segment popularity and revenue contribution.
* **Driver Utilization:** Evaluating fleet performance and availability metrics across core geographic clusters.

### ⏱️ 4. Customer Experience & Ratings
* **Driver & Passenger Feedback:** Tracking average rating distributions to evaluate service quality and identify poor-performing operational areas.
* **Booking Trends:** Visualizing demand spikes across hours of the day, days of the week, and seasonal intervals to forecast fleet supply requirements.

---

## 📁 Repository Structure

* **`dash.pbix`**: The master Power BI Desktop file containing the interactive visual reporting layers, star-schema data model, and custom calculated columns/measures.
* **`Ola Trips Operational Dashboard Analysis.pptx`**: An executive presentation deck translating dashboard visuals into high-level business insights, conclusions, and operational recommendations.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **BI Platform:** Power BI Desktop
* **Data Modeling:** Star Schema configurations, fact/dimension table designs, and relationship management.
* **Business Analytics:** Executive Presentation, Key Performance Indicator (KPI) architecture, Operational Reporting, and Trend Forecasting.

---

## 🚀 How to Explore the Project

1. **Review the Presentation:** Open `Ola Trips Operational Dashboard Analysis.pptx` to quickly digest the strategic insights, operational summaries, and business recommendations discovered during the analysis.
2. **Interact with the Live Model:**
   * Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
   * Clone this repository to your local system:
     ```bash
     git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
     ```
   * Open the `dash.pbix` file locally in Power BI Desktop to interactively filter, slice, and drill down into the ride-sharing dataset.
