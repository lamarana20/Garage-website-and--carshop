#  Garage & Car Shop Website

[![Project Status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/lamarana20/Garage-website-and--carshop.git)
[![Astro](https://img.shields.io/badge/Astro-0.33.2-blue)](https://astro.build/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Welcome to the **Garage & Car Shop** project, a modern website built with **Astro** and **Tailwind CSS**. Users can browse available vehicles, book services, and contact the garage.

---

## 🔗 Project Link

Check out the GitHub repository: [Garage & Car Shop](https://github.com/lamarana20/Garage-website-and--carshop.git)

---

##  Project Structure

```text
/
├── public/                
│   ├── favicon.svg
│   └── images/           # Garage and vehicle images
├── src/
│   ├── assets/           
│   │   └── astro.svg
│   ├── components/       
│   │   ├── Welcome.astro
│   │   ├── About.astro
│   │   ├── Hero.astro
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── Service.astro
│   │   └── Contact.astro
│   ├── layouts/          
│   │   └── Layout.astro
│   └── pages/            
│       ├── index.astro
│       └── Inventory.astro  <-- Main vehicle listing
├── vehicles.json         # Vehicle data source
└── package.json
