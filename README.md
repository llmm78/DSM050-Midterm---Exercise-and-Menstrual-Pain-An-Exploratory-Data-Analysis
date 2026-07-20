# DSM050-Midterm---Exercise-and-Menstrual-Pain-An-Exploratory-Data-Analysis

## Project description

This project performs an exploratory data analysis (EDA) on the mcPHASES dataset. Specifically, this analysis aims at assessing the relationship between exercise and self-report physical and mood symptoms. 

## Data Access
The **dataset** used in this project is publicly available from the mcPHASES study§. However, **cannot be hosted directly in this 
repository**, due to licensing restrictions! 
(§ B. Lin, J. Y. Li, K. Kalani, K. Truong, and A. Mariakakis, “mcPHASES: A Dataset of Physiological, Hormonal, and Self-reported Events and Symptoms for Menstrual Health Tracking with Wearables.” PhysioNet. doi: 10.13026/ZX6A-2C81.)

In PhysioNet Credentialed Health Data Use Agreement 1.5.0 it is stated that: "If I am granted access to the database:...I will not share access to PhysioNet restricted data with anyone else."

https://www.physionet.org/content/generated-codes-low-resource/view-dua/1.0.0/

**You must create a PhysioNet account** (please note, no additional training required!). 
Please download the data directly from the official source:

https://physionet.org/content/mcphases/1.0.0/

* **mcPHASES Study Data:** 
### Required Files

1. `subject-info.csv`
2. `hormones_and_selfreport.csv`
3. `active_zone_minutes.csv`

---

## Repository Structure
* `data/` : Local folder for the downloaded CSV files (empty on GitHub).
* `notebook.ipynb` : The Jupyter Notebook containing all data cleaning and visualizations.
* `.gitignore` : Excludes local temporary files and raw data.
* `LICENSE` : MIT License.
