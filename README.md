# Exploratory-Data-Analysis-with-Python
Recently, I worked on an exciting project involving a 𝗖𝗮𝗿𝘀 𝗗𝗮𝘁𝗮𝘀𝗲𝘁, which included details like car models, manufacturers, engine types, prices, and more. Here's a quick rundown of the process I followed:

![Image](https://github.com/user-attachments/assets/14b9ca6c-7f04-45c9-9703-b7bbac89f527)

## 1. 𝗟𝗼𝗮𝗱𝗶𝗻𝗴 𝘁𝗵𝗲 𝗗𝗮𝘁𝗮𝘀𝗲𝘁 📊 
I started by loading the dataset and used df.info() and df.shape to check the data types and the shape of the DataFrame.

## 2. 𝗗𝗿𝗼𝗽𝗽𝗶𝗻𝗴 𝗜𝗿𝗿𝗲𝗹𝗲𝘃𝗮𝗻𝘁 𝗖𝗼𝗹𝘂𝗺𝗻𝘀 🛠️
Not all columns contribute to our model's accuracy, so I removed irrelevant ones like "Engine Fuel Type," "Market Category," and "Vehicle Style" using the df.drop() function. This step is crucial to ensure our model isn't skewed by unnecessary data.

## 3. 𝗥𝗲𝗻𝗮𝗺𝗶𝗻𝗴 𝗖𝗼𝗹𝘂𝗺𝗻𝘀 𝗳𝗼𝗿 𝗖𝗹𝗮𝗿𝗶𝘁𝘆 ✏️ 
I then renamed some columns to make them more meaningful for model training.

![image](https://github.com/user-attachments/assets/8236c439-8b87-4d6c-a032-73c4f0f6f6f9)


## 4. 𝗛𝗮𝗻𝗱𝗹𝗶𝗻𝗴 𝗗𝘂𝗽𝗹𝗶𝗰𝗮𝘁𝗲𝘀 & 𝗠𝗶𝘀𝘀𝗶𝗻𝗴 𝗩𝗮𝗹𝘂𝗲𝘀 🚮 
I used df.drop_duplicates() to remove any duplicate records and dropped rows with missing values to prevent them from affecting the model's performance.

## 5. 𝗗𝗲𝗮𝗹𝗶𝗻𝗴 𝘄𝗶𝘁𝗵 𝗢𝘂𝘁𝗹𝗶𝗲𝗿𝘀 🚨 
Outliers can drastically impact model accuracy, so I visualised them using Seaborn's boxplots. I focused on columns with numeric data and applied the IQR method (Q3 - Q1) to remove outliers. Additionally, I used the Z-score technique to further refine the dataset.

## 6. 𝗗𝗮𝘁𝗮 𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻 - 𝗧𝗵𝗲 𝗙𝘂𝗻 𝗣𝗮𝗿𝘁! 
🎨 Finally, I dived into data visualisation using Seaborn to uncover relationships between data points. I explored various plots like Displot, CountPlot, BarPlot, ScatterPlot, and more.
