# IBM Applied Data Science Capstone

**Part of the IBM Data Science Professional Certificate (Course 10 of 10)**

This repository contains the comprehensive project work for the SpaceX Falcon 9 first-stage landing prediction. The goal is to predict whether the first stage of a Falcon 9 rocket will land successfully to determine the cost of a launch.

## 🚀 Project Structure

### Phase 1: Data Collection & Wrangling

The foundation of the project involves gathering data from multiple sources and cleaning it for analysis.

* **1 - Data Collection API**: `Hands-on Lab_ Complete the Data Collection API Lab.ipynb`
* Using SpaceX API to retrieve launch data.


* **2 - Web Scraping**: `Hands-on Lab_ Data Collection with Web Scraping.ipynb`
* Scraping Wikipedia to supplement the dataset with launch records.


* **3 - Data Wrangling**: `Hands-Hands-On Lab_ Data Wrangling.ipynb`
* Handling missing values, converting outcomes into binary labels (1 for success, 0 for failure), and exploratory preprocessing.



### Phase 2: Exploratory Data Analysis (EDA)

Analyzing the data through queries and visualization to find patterns.

* **4 - SQL Analysis**: `Hands-on Lab Complete the EDA with SQL.ipynb`
* Running complex queries to understand payload mass, booster versions, and landing success rates.


* **5 - Data Visualization**: `jupyter-labs-eda-dataviz.ipynb`
* Using Pandas, Matplotlib, and Seaborn to visualize trends (e.g., Flight Number vs. Launch Site).



### Phase 3: Interactive Analytics & Geospatial Mapping

Using maps and dashboards to provide a more intuitive understanding of launch sites.

* **6 - Launch Site Mapping**: `lab_jupyter_launch_site_location.ipynb`
* Utilizing **Folium** to create interactive maps and mark success/failure clusters at various launch pads.


* **7 - Interactive Dashboard**: `spacex_dash_app.py` & `Build an Interactive Dashboard with Ploty Dash.ipynb`
* A real-time dashboard built with **Plotly Dash** featuring dropdowns and range sliders to filter data by payload and site.



### Phase 4: Predictive Analysis (Machine Learning)

The "core" of the capstone where the prediction model is built.

* **8 - Machine Learning Prediction**: `SpaceX_Machine Learning Prediction_Part_5.ipynb`
* Training and tuning models (Logistic Regression, SVM, Decision Trees, and K-Nearest Neighbors).
* Evaluating performance using confusion matrices and accuracy scores.



### Phase 5: Final Reporting

* **9 - Executive Summary**: `robert-spacex-booster-prediction-report.pdf`
* The final presentation deck summarizing the methodology, insights, and the best-performing model for stakeholders.



---

## 🛠️ Tech Stack

* **Languages:** Python, SQL
* **Libraries:** Pandas, NumPy, Scikit-learn, Folium, Plotly Dash, Matplotlib, Seaborn, BeautifulSoup
* **Tools:** Jupyter Notebooks, IBM Cloud DB2

