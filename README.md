# BookMyConsultation Frontend

[![GitHub stars](https://img.shields.io/github/stars/syntax2/bookmyconsultation-frontend?style=social)](https://github.com/syntax2/bookmyconsultation-frontend/stargazers)

> A React‑powered frontend for **BookMyConsultation**—your one‑stop web app to search medical specialists, view availability, book appointments, and rate doctors worldwide.

## Table of Contents

- [Features](#features)  
- [Architecture Overview](#architecture-overview)  
- [Prerequisites](#prerequisites)  
- [Getting Started](#getting-started)  
  - [Clone the Repo](#clone-the-repo)  
  - [Install Dependencies](#install-dependencies)  
  - [Run in Development](#run-in-development)  
  - [Build for Production](#build-for-production)  
  - [Running Tests](#running-tests)  
- [Available Scripts](#available-scripts)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features

- 🔍 **Doctor Search** by specialty, name, or location  
- 📅 **Real‑time Time Slots** filtered by existing bookings  
- ✅ **Appointment Booking** with confirmation UI  
- ⭐ **Rating & Reviews** for consulted doctors  
- 👤 **User Authentication** (Sign up / Sign in)  
- 🔒 **Secure Token‑based Sessions**  

---

## Architecture Overview

The **BookMyConsultation** frontend is built with:

- **Create React App** – zero‑config bootstrapping  
- **React Router** – client‑side routing  
- **Axios** – HTTP client for REST API calls  
- **Context API** (or Redux) – application‑wide state  
- **CSS Modules** (or styled‑components / SCSS) – scoped styling  

Screenshots of the working UI can be found in the `./screenshots/` folder.

---

## Prerequisites

- **Node.js** v10 or higher  
- **npm** v6 or higher (bundled with Node.js)  

---

## Getting Started

### Clone the Repo

```bash
git clone https://github.com/syntax2/bookmyconsultation-frontend.git
cd bookmyconsultation-frontend
