# **HEIC-to-JPEG Converter for Machine Learning**  

## **Overview**  
Many machine learning libraries, including TensorFlow and PyTorch, lack native support for **.HEIC (High-Efficiency Image Coding)** format, despite its superior image quality and compression. This project provides a solution by **converting HEIC images to JPEG** while ensuring **80-90% quality retention** from the original image.  

This repository contains a **Jupyter Notebook** that allows users to **convert HEIC images to JPEG**, compare quality differences, and analyze how the conversion affects machine learning workflows.  

## **Getting Started**  

### **Prerequisites**  
Ensure you have the following installed before running the notebook:  

- Python (≥3.8)  
- Jupyter Notebook  
- Required Python libraries:  
  ```bash
  pip install pillow pyheif matplotlib numpy
  ```  

### **Opening the Notebook**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/heic-to-jpeg-ml.git
   cd heic-to-jpeg-ml
   ```  
2. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```  
3. Open `HEIC_to_JPEG_Analysis.ipynb` and run the cells step by step.  

## **Observing the Image Differences**  
The notebook will:  

✅ **Load a sample HEIC image** and display it (if supported).  
✅ **Convert the HEIC image to JPEG** while preserving 80-90% of the original quality.  
✅ **Display side-by-side comparisons** between the original HEIC and converted JPEG image.  
✅ **Analyze pixel differences** to measure quality loss.  

## **Expected Results**  
- The JPEG image should **closely resemble the HEIC image**, retaining most details.  
- Some minor compression artifacts might be visible, but they **will not significantly impact ML training** in most cases.  
- The converted JPEG file will be **larger than HEIC but more compatible** with ML frameworks.  

## **Future Scope**  
- Further optimize conversion to minimize quality loss.  
- Explore native **TensorFlow integration** for direct HEIC support.  
- Implement **batch conversion** for large datasets.  

## **Contributing**  
We welcome contributions to improve this tool! Feel free to fork the repository, make enhancements, and submit a pull request.  

## **License**  
This project is open-source under the **MIT License**.  

---

This README provides clear instructions on using the notebook and what users can expect from it. Let me know if you need any refinements! 🚀
