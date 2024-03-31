# Lead-a-Data-Project

## Optimization of Sports Performance Through Activity Monitoring: Focused on the Vacation Period 🏃🏽‍♀️🏋🏻‍♂️


## ➡️ Some recommendations to read or execute this project : 🤗

 * 🟠 🔗 **Dataset** :  Have a look at dataset used (csv file) <ins>*time_series_data_human_activities.csv*</ins>  
   
    * 👉🏽 The dataset is **udge** (*1 million rows*) 
        * In case you want to execute this file, we recommend to read/execute it with **Google Colab** ⭐️ 


 * 🟢 🔗 **Notebook**: here is the project itself, go check <ins>*activity_recognition_mellano_dousse.ipynb</ins>
   
    * 👉🏽 We **sampled dataset** in some parts of the Exploratory Data Analysis because of big amount of data 
    * 👉🏽 Again, for deep learning model execution we recommand **Google Colab** usage ⭐️ 

* 🔵 Thanks for your attention, **Enjoy this project!** ✨


👇🏽 *Final project description for Jedha certification of Bloc 6 * 👇🏽

---
---

# Optimization of Sports Performance Through Activity Monitoring: Focused on the Vacation Period 

## Goal 🎯

* In the realm of sports, one of the most significant challenges lies in maintaining an **optimal level of performance and physical condition during rest and vacation periods**. 🏃🏽‍♀️
* Coaches and physical trainers face the daunting task of **ensuring that athletes maintain an adequate level of physical activity** and make the most of this recovery time without compromising their physical state or athletic ability. 
* It is in this context that **monitoring athletes' activities** during vacations could ensure a smooth transition between training and rest periods. 📲
`
## Scope 🖼️

* In this regard, the **integration of monitoring technologies** based on cell phones or smartwatches could be a solution. 
* These devices not only provide a wide range of **physical activity tracking functions** but also offer the ability to collect detailed data on the **user's movement and performance**. 💪🏽
* In many cases, athletes forget to save the data from their watch to be able to later share it, or they avoid sharing it to avoid facing such **responsibilities**. ✅
* Having data like this, especially during shorter vacation periods (for example, a free weekend), would be useful for a coach to know what type of activities the athlete was doing and how to approach the beginning of the return to activities.


## Dataset 🖥️

### **What is the dataset about?** 👇🏽

* We have found a dataset where the information collected from an **accelerometer through cell phones of 36 different users** is available. 

* Each user performed some or all of these actions: 
    * **Sitting** 🪑
    * **Standing**🧍🏻‍♀️
    * **Walking **🚶🏻‍♀️
    * **Jogging** 🏃🏽‍♀️
    * **Upstairs** 🪜⬆️
    * **Downstairs** 🪜⬇️

* The objective of this project is to **create a model**  so that through the collected data, the action performed can be classified.

 ### **The dataset have following format**: 👩🏽‍💻
 
 [user],[activity],[timestamp],[x-axis],[y-axis],[z-axis];
 
  🔹 **User**: 1 to 36 

  🎯 **Activity**: nominal, {Walking, Jogging, Sitting, Standing, Upstairs, Downstairs} 

  🔹 **Timestamp**: numeric, generally the phone's uptime in nanoseconds."

  🔹 **X-axis**

  🔹 **Y-axis**

  🔹 **Z-axis**
