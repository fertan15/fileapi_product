# 📦 Lokalooks Product API  

[![Made with JSON](https://img.shields.io/badge/JSON-lightgrey?logo=json&logoColor=black)](https://www.json.org/)  
[![Hosted on GitHub Pages](https://img.shields.io/badge/Hosted-GitHub%20Pages-black?logo=github)](https://fertan15.github.io/fileapi_product/products.json)  
[![Status](https://img.shields.io/badge/API-Dummy%20Educational-blue)](#-purpose)  

This repository provides a **static JSON API** containing product data for the [Lokalooks E-commerce](https://github.com/fertan15/Lokalooks_E-commerce) project.  
It is deployed using **GitHub Pages** and can be accessed publicly.  

---

## 🔗 API Endpoint  

The JSON data is available here:  
👉 [https://fertan15.github.io/fileapi_product/products.json](https://fertan15.github.io/fileapi_product/products.json)  

---

## 🗂️ Data Structure  

The API returns an array of product objects in JSON format.  

### Example  

```json
[
{
        "id": 1,
        "brand": "ERIGO",
        "name": "Erigo T-Shirt Oversize Antelope Black Unisex",
        "price": "Rp 103.000",
        "image": "./img/id-11134201-7r98u-lxgl1nqxmcvga0(2).jpg",
        "description": "Raih gaya kasual maksimal dengan Erigo T-Shirt Oversize Antelope Black Unisex. Desainnya yang oversized memberikan kenyamanan sekaligus tampil modis. T-shirt ini hadir dengan warna hitam klasik yang mudah dipadukan dengan berbagai outfit, serta detail grafis Antelope yang menambah kesan unik dan trendi.",
        "category": ["man", "woman"],
        "rating": 4.3,
        "buyed" : 5,
        "image1": "./img/id-11134201-7r98v-lxdi6hhlmyzw03(1).jpg",
        "image2": "./img/id-11134201-7r98w-lxdi6hdze78e32(1).jpg"
        
    },
    {
        "id": 2,
        "brand": "ERIGO",
        "name": "Erigo Chino Pants Sirius Black Unisex",
        "price": "Rp 175.000",
        "image": "./img/id-11134201-7r98t-lu4f2p0138yxdc(2).jpg",
        "description": "Cotton twill (stretch) sebagai bahan celana ini membuat penggunanya nyaman & bebas bergerak saat beraktivitas. Bahan stretch dengan cuttingan slim-fit menyegarkan tampilan outfit, cocok dipadukan dengan T-shirt maupun kemeja. Tampil casual sekaligus formal dapat diwujudkan dengan celana ini! Kami menyediakan pilihan panjang celana; pendek & panjang, yang bisa dipilih sesuai kebutuhan.",
        "category": ["man", "woman"],
        "rating": 0,
        "buyed" : 0,
        "image1": "./img/id-11134201-7r98t-lu4f2p0b2uvj75(1).jpg",
        "image2": "./img/id-11134201-7r992-lu4f2p0l2g47de(1).jpg"
    },
]

```
---
## 🛠️ How to Use
---
You can fetch this data in JavaScript using the fetch() API:
```javascript
fetch("https://fertan15.github.io/fileapi_product/products.json")
  .then(response => response.json())
  .then(data => {
    console.log(data); // Array of product objects
  })
  .catch(error => console.error("Error fetching product data:", error));
```
You can also test the API directly in your browser or tools like Postman.

---
## 🎓 Purpose
---
> Provides a dummy product API for educational use.
> Powers the Lokalooks E-commerce project.
> Demonstrates how a front-end app can consume external data.
> Helps beginners practice API integration without a backend server.

## ⚠️ Disclaimer
The product images and names used in this dataset are for demo and educational purposes only.
This API is not affiliated with or endorsed by any brand.
