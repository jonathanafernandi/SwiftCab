# SwiftCab

**SwiftCab Super App: Online Taxi, Delivery, Payment**  
A responsive multi-page website built as a project for the **COMP6800001 – Human-Computer Interaction** course (Bina Nusantara University, School of Computer Science).

## Table of Contents

- [Overview](#overview)
- [Live Demo](#live-demo)
- [Design Resources](#design-resources)
- [Group Members](#group-members)
- [Project Structure](#project-structure)
- [Pages](#pages)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Features](#features)
- [Notes](#notes)

## Overview

SwiftCab is a fictional "super app" concept inspired by on-demand platforms, offering transport, delivery, payment, food/shopping, and entertainment services in one integrated experience. This repository contains the static website prototype (HTML, CSS, and JavaScript) developed to demonstrate the Human-Computer Interaction principles applied in its interface design, including navigation usability, responsive layout, and form validation.

## Live Demo

Check out the live site: [https://jonathanafernandi.github.io/SwiftCab/](https://jonathanafernandi.github.io/SwiftCab/)

## Design Resources

- **Figma Design (Website Interface):** [View on Figma](https://www.figma.com/design/QfIGsx0554BAX5JZuLVg9M/SwiftCab)
- **Figma Prototype (Interactive Flow):** [View Prototype](https://www.figma.com/proto/QfIGsx0554BAX5JZuLVg9M/SwiftCab)

## Group Members

| Name | Student ID |
|---|---|
| Jonathan Alvindo Fernandi | 2602089143 |
| Riccardo Davinci | 2602089811 |
| Edgar Doli Matius | 2602204821 |

**Class:** LC01 (Group 3)

## Project Structure

```
SwiftCab/
├── html/
│   ├── home.html
│   ├── driver.html
│   ├── about.html
│   ├── products.html
│   └── download.html
├── css/
│   ├── home.css
│   ├── driver.css
│   ├── about.css
│   ├── products.css
│   └── download.css
├── js/
│   ├── home.js
│   ├── driver.js
│   ├── about.js
│   └── products.js
├── img/
│   ├── swiftcab-logo.svg
│   ├── home/
│   ├── driver/
│   ├── about/
│   ├── products/
│   └── download/
├── docs/
│   └── LC01-Kel3_AoL-Project-Dokumentasi.pdf
└── README.md
```

## Pages

| Page | Description |
|---|---|
| **Home** | Landing page with hero banner, impact stats, and growth achievements. |
| **Driver Partners** | Login/register page for prospective drivers, with phone number, email, gender, date of birth, and ID number fields, including client-side validation. |
| **About** | Company milestones timeline from local motorcycle taxis to a multinational super app. |
| **Products** | Overview of SwiftCab's product lines: transport & logistics, payments, food & shopping, and entertainment. |
| **Download** | Call-to-action page for downloading the SwiftCab mobile app. |

## Tech Stack

- **HTML**: semantic page structure across five pages
- **CSS**: custom responsive styling with multiple breakpoints
- **JavaScript**: sticky header hide-on-scroll behavior, mobile burger menu toggle, and form validation
- **[Font Awesome 6.4.0](https://fontawesome.com/)**: social and UI icons
- **[Google Fonts - Maven Pro](https://fonts.google.com/specimen/Maven+Pro)**: primary typeface

## Getting Started

### Prerequisites

- A modern web browser
- (Optional) [Visual Studio Code](https://code.visualstudio.com/) with the **Live Server** extension for local development
- Git

### Clone the Repository

```bash
git clone https://github.com/jonathanafernandi/SwiftCab.git
cd SwiftCab
```

### Run Locally

Simply open any HTML file directly in your browser:

```bash
open html/home.html    # macOS
start html/home.html   # Windows
```

Or serve it with Live Server for hot-reloading during development.

## Features

- **Responsive navigation**: collapsible burger menu on smaller screens, with a hide-on-scroll header for a cleaner reading experience.
- **Driver onboarding flow**: login form with country phone code selector, and a register form with real-time validation (name length, email format, required fields, and minimum age of 18 for drivers).
- **Company storytelling**: an "About" milestones timeline highlighting SwiftCab's growth.
- **Product showcase**: categorized display of all SwiftCab services across transport, payments, food/shopping, and entertainment.
- **App download CTA**: dedicated page linking to the SwiftCab mobile app download links.

## Notes

- This project is a front-end prototype for academic purposes (HCI course), built to demonstrate usability and interaction design principles rather than a production-ready backend service.
- All company names, statistics, and branding ("SwiftCab", "PT Swift Cab Tbk.") are fictional and created for this project.
- The project documentation is available in `docs/LC01-Kel3_AoL-Project-Dokumentasi.pdf`.
