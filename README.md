# 📊 Funnel Analysis Project

This project demonstrates an end-to-end data analysis workflow — from data generation and cleaning to visualization and dashboard creation.

The goal of this project is to perform **Funnel Analysis** using a synthetic dataset and present insights through an interactive dashboard.

---

## 🚀 Project Overview

In this project, I:

- Generated **fake business data** using a Python data generation library  
- Cleaned and prepared the dataset using Python  
- Performed **Exploratory Data Analysis (EDA)**  
- Visualized patterns using plotting libraries  
- Built an interactive **Funnel Dashboard** in Power BI  

This simulates how real companies track user/customer movement through stages like:

**Visited → Signed Up → Added to Cart → Purchased**

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data generation & analysis |
| Faker (Fake Data Library) | Creating synthetic dataset |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Basic visualizations |
| Seaborn | Statistical data visualization |
| Power BI | Dashboard & funnel reporting |

---

## 📂 Project Workflow

### 1️⃣ Data Generation
- Created a synthetic dataset representing customer journey stages  
- Includes user IDs, actions, timestamps, and conversion steps  

### 2️⃣ Data Cleaning
Performed using **Pandas**:
- Removed missing values  
- Standardized column formats  
- Filtered invalid records  
- Prepared data for funnel calculation  

### 3️⃣ Exploratory Data Analysis (EDA)
Used **Matplotlib** and **Seaborn** to:
- Analyze stage-wise drop-offs  
- Identify conversion trends  
- Compare user behavior  
- Visualize distributions  

### 4️⃣ Funnel Analysis
Calculated:
- Total users at each stage  
- Drop-off percentage  
- Conversion rate between steps  

### 5️⃣ Dashboard Creation
Built a **Power BI Dashboard** showing:
- Funnel chart  
- Conversion rates  
- Step-wise user counts  
- Key KPIs  

---

## 📈 Key Insights (Example)

- Major drop observed between **Signup → Add to Cart**  
- Purchase conversion rate is significantly lower than initial traffic  
- Funnel visualization helps identify where users are lost  

---

## 🧠 What I Learned

- How to simulate real-world data  
- Data cleaning techniques in Pandas  
- Visualization with Matplotlib & Seaborn  
- Understanding customer journey analytics  
- Building analytical dashboards in Power BI  

---

## 📌 How to Run the Project

```bash
pip install pandas matplotlib seaborn faker
```

Then run the Python notebook/script for:
- Data generation  
- Cleaning  
- Visualization  

Dashboard can be opened using the `.pbix` file in Power BI.

---

## 📎 Future Improvements

- Use real-world dataset  
- Add time-based funnel tracking  
- Apply machine learning for conversion prediction  
- Automate data pipeline  

---

## 👤 Author

**Umed**  
Aspiring Data Analyst | Python | Power BI | Data Visualization
# funnel--analysis-project
