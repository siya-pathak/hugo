---
date: 2023-12-28T11:25:05-04:00
description: "A website built for classifying a person as one of the five famous sports personalities"
featured_image: "/images/pizzabae.PNG"
tags: ["Python", "HTML", "CSS", "JavaScript", "Flask"]
title: "SportifyFive - Sports Person Classifier"
---

* Objective: Image classification project focusing on identifying five sports personalities by dragging and dropping their images onto a website.

* Process Overview: This project involves scraping images of sports personalities for classification. It employs Haar Cascade for detecting faces and eyes to ensure image quality. Additionally, Wavelet Transforms are used for feature engineering to enhance image edges and identify facial features.

* Model Building: Utilizing SVM with a linear kernel, the project achieved an accuracy of around 85%. The model, fine-tuned via GridSearchCV, resulted in Pickle and JSON files containing the model directories.

* Python Flask Server: The project's function involves conducting image classification using exported Pickle and JSON files. This backend serves as the backbone for the user interface (UI) application.

* Web UI Development: The project's frontend is built using straightforward technologies like HTML, CSS, and JavaScript. The UI allows image drag-and-drop and converts images to base64 strings for backend processing. Interaction occurs via HTTP calls between the UI, powered by jQuery, and the backend Python Flask Server for image classification.

* Final Outcome: The project presents an intuitive website interface where users can drop images to identify specific sports personalities. The backend Python Flask Server manages the classification process, providing the identified sportsperson's name.

[Link to the GitHub repository](https://github.com/siya-pathak/SportifyFive)