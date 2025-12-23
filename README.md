<pre>
                         ██████╗ ████████╗██╗██╗   ██╗ █████╗ ██╗   ██╗██████╗ ██╗      ██████╗  █████╗ ██████╗ 
                        ██╔═══██╗╚══██╔══╝██║██║   ██║██╔══██╗██║   ██║██╔══██╗██║     ██╔═══██╗██╔══██╗██╔══██╗
                        ██║   ██║   ██║   ██║██║   ██║███████║██║   ██║██████╔╝██║     ██║   ██║███████║██║  ██║
                        ██║   ██║   ██║   ██║╚██╗ ██╔╝██╔══██║██║   ██║██╔═══╝ ██║     ██║   ██║██╔══██║██║  ██║
                        ╚██████╔╝   ██║   ██║ ╚████╔╝ ██║  ██║╚██████╔╝██║     ███████╗╚██████╔╝██║  ██║██████╔╝
                         ╚═════╝    ╚═╝   ╚═╝  ╚═══╝  ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═════╝ 
</pre>



<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/EN-F2C94C?style=for-the-badge&logo=googletranslate&logoColor=000000">
  </a>
  <a href="README.ru.md">
    <img src="https://img.shields.io/badge/RU-C0392B?style=for-the-badge&logo=googletranslate&logoColor=FFFFFF">
  </a>
</p>





<p align="center">
  <img src="https://img.shields.io/badge/Python-9FEF00?style=for-the-badge&logo=python&logoColor=000000">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Google%20API-4285F4?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/XML-FF8C00?style=for-the-badge">
</p>



## Overview

**OtivaUpload** is a web service designed to significantly speed up and simplify bulk uploads of listings to Avito. The service automates routine tasks involved in preparing ads: data structuring, content uniqueness, image processing, and XML feed generation.
The main goal is to reduce manual work, increase upload speed, and improve listing uniqueness.


## Key Features

### Google Sheets Integration
- Automatic generation of Google Sheets templates
- Templates include all required fields for selected Avito categories
- One table can be used to manage dozens or hundreds of listings

### Content Uniqueness
- Title generation
- Description generation
- Price randomization
- Flexible logic per category
- Helps avoid duplicate content issues

### Image Upload & Processing
- Bulk image upload
- Image uniqueness processing
- Prepared images fully ready for Avito upload

### XML Feed Generation
- Automatic generation of ready-to-use XML feeds
- XML complies with Avito requirements
- Feed can be uploaded directly without manual editing

### Listing Management
- Project-based structure
- Category-level configuration
- Listing limits control
- Tracking listing validity period

## Typical Workflow

1. Create a project
2. Select an Avito category
3. Generate a Google Sheets template
4. Fill or import data
5. Upload and process images
6. Generate XML feed
7. Upload XML to Avito


## Security

- Secrets are stored outside source code
- Environment-based configuration
- Isolated access per project
- Controlled API usage limits


## Project Status

The project is under active development.  
New features and improvements are added continuously.
