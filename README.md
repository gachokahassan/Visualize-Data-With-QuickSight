# Visualize Data with Amazon QuickSight

## Project Overview
This project demonstrates how to use Amazon QuickSight to analyze and visualize data stored in an S3 bucket. By leveraging QuickSight's intuitive interface, I created interactive dashboards that offer insights into release trends for Netflix titles.

## Key Deliverables
1. **Dataset Upload**:
   - Uploaded `netflix_titles.csv` to S3.
   - Edited `manifest.json` to ensure QuickSight could interpret the dataset.

2. **Account Setup**:
   - Created a free QuickSight account and connected it to S3.
   - Disabled paid features like Paginated Reports.

3. **Visualizations**:
   - Built bar charts and pie charts to analyze the release trends of Netflix titles by year and type.
   - Added filters to focus on data from 2015 onwards.

4. **Dashboard**:
   - Customized and organized visualizations into an interactive dashboard.
   - Exported the dashboard as a PDF for sharing.

## Challenges and Lessons Learned
- **Challenge**: Editing the `manifest.json` to correctly reference the S3 dataset.
- **Lesson Learned**: QuickSight's drag-and-drop interface simplifies visualization, making it accessible for beginners.

## Outcome
- Created an interactive dashboard highlighting release trends by year and type, focusing on titles released after 2015.
- Exported the dashboard as a shareable PDF.

## Skills/Tools Used
- **AWS Services**: S3, QuickSight
- **Other Tools**: Manifest JSON editing, Data visualization techniques

---

## Project Files
- `netflix_titles.csv`: The dataset used for analysis.
- `manifest.json`: Metadata file for connecting the dataset to QuickSight.

---

## Steps to Reproduce
1. **Upload Dataset to S3**:
   - Store `netflix_titles.csv` in an S3 bucket.
   - Edit `manifest.json` with the correct S3 URL of the dataset.

2. **Set Up QuickSight**:
   - Create a QuickSight account and connect it to the S3 bucket.

3. **Create Visualizations**:
   - Use drag-and-drop features to build charts and customize filters.

4. **Export Dashboard**:
   - Review the dashboard for clarity and export it as a PDF.

---

## Screenshots
1. **Visualization: Netflix Titles by Release Year**
   ![Netflix Titles by Year](./Images/Netflix_Titles_Year.png)

2. **Dashboard Layout**
   ![Dashboard](./Images/Dashboard_Layout.png)

---

## Author
**Hassan Gachoka**  
[LinkedIn](https://linkedin.com/in/gachokahassan)

---
