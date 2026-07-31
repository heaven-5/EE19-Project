# EE19-Project

**GET 324 Mini Project – Group EE19**

Concrete Bridge Deck Crack Detection using Deep Learning

---

## Overview

This project detects cracks on concrete bridge deck surfaces from images.  
It combines two neural networks:

1. **Anomaly Detector** – verifies that the uploaded image is actually a concrete surface  
2. **Crack Detection Model** – classifies the surface as *Cracked* or *Non-Cracked*

A simple Streamlit web app lets users upload an image and instantly get a prediction with confidence score.

---

## Features

- Upload JPG / JPEG / PNG images
- Automatic rejection of non-concrete images (anomaly detection)
- Binary classification: **Cracked** vs **Non-Cracked**
- Confidence score for every prediction
- Handles uncertain predictions (0.4–0.6 range)
- Lightweight and easy to run locally

---

## Project Structure

