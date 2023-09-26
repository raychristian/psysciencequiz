# Psy Science: Quiz & Certificate Generation

![Psoirée Logo](https://static.wixstatic.com/media/4d3b6d_9a8391969e4444a29fcf745d3c589885~mv2.png)

## Description

Psy Science is a comprehensive solution designed for course participants to undertake a quiz and, upon successful completion, receive a custom PDF certificate. The quiz is embedded in a Wix site using Google Forms through an iFrame. This repository contains the automation scripts and integrations to make this flow possible.

## Table of Contents

- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Google Form Quiz**: Tailored to course content and branded with Psoirée aesthetics.
  
- **Google Sheet Integration**: Automated data storage of quiz responses.
  
- **Automated Grading**: Google Apps Script-based grading system.
  
- **PDF Certificate Generation**: On successful grading, custom certificates are generated using the PDFcrowd API.
  
- **User Notifications**: Users receive links to download their certificates.
  
- **Testing & QA**: Comprehensive testing to ensure a smooth user experience.

## Setup & Installation

1. Clone this repository:
```
git clone [repository-link]
```
2. Ensure you have access to the linked Google Form and Google Sheet.
3. Set up the required API keys for PDFcrowd integration.
4. Adjust the placeholders in the script as per your Google Sheet's layout.

## Usage

1. Participants can access the quiz through the Wix website.
2. Upon successful completion, they are graded automatically.
3. If they pass the quiz, a unique certificate ID is generated.
4. They then receive a custom PDF certificate either through a direct link or an email notification.

## Contribution

Feel free to fork this repository and propose changes. All pull requests are welcome. Kindly ensure any changes proposed are well documented.

## License

This project is licensed under the MIT License. Refer to the `LICENSE` file for more information.

## Acknowledgments

- [Psoirée](https://www.psoiree.com) for the vision and branding.
- ChatGPT for help coding and debugging
- Google Apps Script & Google Cloud Platform for the robust backend infrastructure.
- PDFcrowd for the certificate generation API.


