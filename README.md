# **US Mental Health Data Analysis and Visualization**  

## **Project Overview**  
The project demonstrates my expertise in sourcing, cleaning, analyzing, and visualizing large-scale mental health datasets, along with proposing data-driven implementation ideas based on the insights. You can find the code in the main.ipynb. 

The primary goal was to extract meaningful insights from nationally representative mental health data to inform actionable strategies to improve behavioral health systems. 

---

## **Dataset**  
- **Source:** National Survey on Drug Use and Health (NSDUH), conducted annually by SAMHSA.  
- **Scope:** The dataset provides comprehensive information on mental health issues and treatments among the civilian, non-institutionalized population aged 12 or older in the United States.  
- **Key Variables:** Out of a total of 2,600 columns, 18 variables were selected for analysis, including:  
  - Demographics  
  - Difficulty markers  
  - Level of impairment  
  - Community program involvement  
  - Psychological distress  

---

## **Steps Performed**  

### **1. Data Sourcing and Preparation:**  
- Obtained the dataset in SPSS format along with a 700-page codebook.  
- Parsed the codebook to identify relevant variables for analysis.  

### **2. Data Cleaning:**  
- Replaced numerical placeholders (e.g., `88` for bad data and `94` for unknown data) with `null` values using Python to prevent interference in calculations.  
- Renamed columns programmatically to improve readability of the dataframe.  

### **3. Data Analysis:**  
- Focused on understanding relationships between variables using correlational analysis.  
- Avoided unnecessary transformations such as standardization in cases where data label meanings could be lost.  

### **4. Visualizations:**  
- Created visualizations to explore:  
  - Psychological distress by race and education.  
  - Community involvement based on English fluency.  
  - Difficulty with basic tasks correlation with level of emotional impairment. 
- Visuals were designed to support data-driven recommendations for interventions.  

### **5. Data-Driven Implementation Ideas:**  
- Proposed strategies informed by the insights, including targeted community programs to improve psychological outcomes for specific demographics.  

---

## **Tools and Technologies**  
- **Data Cleaning and Analysis:** Python (Pandas, NumPy)  
- **Visualization:** Tableau  
- **Dataset Format:** SPSS  

---

## **Visualizations**  
The project includes a Tableau dashboard showcasing key insights. The dashboard provides an interactive view of the analysis and preliminary implementation ideas.  
[https://public.tableau.com/app/profile/priscilla.morales/viz/NMH_22_Visuals/Dashboard1](#)  

---

## **Future Directions**  
This project serves as a starting point for deeper analysis and more robust visualizations. Future improvements could include:  
- Expanding the scope of variables analyzed.  
- Incorporating additional datasets for a broader perspective.  
- Developing predictive models to forecast outcomes based on selected variables.  

---

