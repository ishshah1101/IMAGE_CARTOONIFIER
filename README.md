# IMAGE_CARTOONIFIER
🚀 Transform your images into stunning cartoon-style art using AI-powered image processing! This project leverages OpenCV, K-means clustering, and adaptive filtering to create vibrant, edge-preserving cartoon effects. Unleash creativity with a touch of innovation! 🎨✨


# 🎨 Cartoonifier - Image to Cartoon Converter  

## 📌 Overview  
This project is an **image cartoonifier** built using **Python** and **OpenCV**. It applies a series of image processing techniques to transform ordinary images into cartoon-like representations. By using **edge detection, color quantization, and bilateral filtering**, we create a fun and visually appealing effect that simplifies colors while preserving essential details.  

## 🚀 Features  
- 📸 **Image Input**: Load any image in common formats (JPG, PNG, etc.).  
- 🎭 **Edge Detection**: Identifies object outlines using **adaptive thresholding**.  
- 🎨 **Color Quantization**: Reduces the number of colors using **K-means clustering**.  
- 🔍 **Noise Reduction**: Applies **bilateral filtering** to smooth colors while keeping edges sharp.  
- 🖼️ **Cartoon Effect**: Combines the edge mask with the processed image to generate a cartoon-style output.  

## 🛠️ Technologies Used  
- **Python**  
- **OpenCV**  
- **NumPy**  
- **Matplotlib**  

## 📌 How It Works  
1. **Read Image**: Load the input image and convert it to RGB format.  
2. **Edge Detection**: Convert the image to grayscale, apply median blur, and detect edges using **adaptive thresholding**.  
3. **Color Quantization**: Use **K-means clustering** to group colors and simplify the image.  
4. **Noise Reduction**: Apply **bilateral filtering** to preserve edges while reducing noise.  
5. **Cartoon Effect**: Merge the processed image with the edge mask to create a **cartoon-style** image.  

## 📂 Project Structure  
```
📦 Cartoonifier
┣ 📂 images # Sample input/output images
┣ 📜 cartoonify.py # Main Python script
┣ 📜 requirements.txt # Dependencies list
┣ 📜 README.md # Project documentation
┗ 📜 process.docx # Technical process documentation
```



## 🖥️ Installation & Usage  

### 1️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```
### 2️⃣ Run the Cartoonifier
```bash
python cartoonify.py --image path/to/image.jpg
```
### 3️⃣ View the Result
The processed image will be displayed using Matplotlib and saved automatically.


## 🔥 Future Enhancements  
- 📌 Add a GUI for user-friendly interaction.  
- 📌 Provide real-time cartoonification using a webcam.  
- 📌 Experiment with **Deep Learning** models for better stylization.  

## 📜 License  
This project is licensed under the **MIT License**.  
