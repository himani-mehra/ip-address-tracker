# IP Address Tracker

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Introduction

IP Address Tracker is a web application that allows users to track and get information about IP addresses and domains. It provides details such as the IP address, location, timezone, and ISP (Internet Service Provider).

## Features

- IP Address and domain tracking.
- Display of location, timezone, and ISP information.
- Interactive map showing the geographical location of the IP address.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Leaflet](https://leafletjs.com/) - An open-source JavaScript library for mobile-friendly interactive maps.
- [Font Awesome](https://fontawesome.com/) - Icon library used for the right arrow icon.

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Web browser (Google Chrome, Mozilla Firefox, etc.)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/ip-address-tracker.git
   ## Usage

1. Open the web browser and go to the project URL or open the `index.html` file.
2. Enter an IP address or domain in the search bar and click the right arrow icon to track.
3. View detailed information about the IP address, location, timezone, and ISP.
4. Explore the interactive map displaying the geographical location.

## Project Structure

- **index.html:** The main HTML file containing the structure of the web page.
- **styles.css:** The stylesheet file for styling the HTML elements.
- **app.js:** The JavaScript file for implementing interactive features and fetching data from the API.
- **config.js:** Configuration file containing the API key.

## API

The project uses the [IPGeolocation API](https://ipgeolocation.io/) to retrieve information about IP addresses and domains. You need to provide your API key in the `config.js` file.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a pull request.

## License

This project is licensed under the MIT License.

