# sabat-MERN-GCP 🌐

![Node.js](https://img.shields.io/badge/Node.js-8CC84B?style=flat-square&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

Welcome to the **sabat-MERN-GCP** repository! This project is an API Rest built using NodeJS, Express, and MongoDB. It serves as a boilerplate for developing applications on Google Cloud Platform (GCP).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The **sabat-MERN-GCP** project aims to simplify the process of building RESTful APIs with a focus on scalability and performance. It leverages the strengths of the MERN stack, along with the robust capabilities of Google Cloud Platform. This makes it an ideal choice for developers looking to create efficient applications.

## Features

- RESTful API architecture
- Built with Node.js and Express
- MongoDB for data storage
- Easy deployment on Google Cloud Platform
- Swagger UI for API documentation
- PM2 for process management
- Scalable and efficient design

## Technologies Used

- **Node.js**: JavaScript runtime built on Chrome's V8 engine.
- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing data in JSON-like documents.
- **Google Cloud Platform**: Suite of cloud computing services.
- **PM2**: Advanced, production process manager for Node.js applications.
- **Swagger**: API documentation framework.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**

   Use the following command to clone the repository:

   ```bash
   git clone https://github.com/joaovlmxs/sabat-MERN-GCP.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd sabat-MERN-GCP
   ```

3. **Install Dependencies**

   Use npm to install the required packages:

   ```bash
   npm install
   ```

4. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add your environment variables. Here’s an example:

   ```plaintext
   MONGODB_URI=your_mongodb_connection_string
   PORT=your_port_number
   ```

5. **Start the Application**

   Use the following command to start the application:

   ```bash
   npm start
   ```

## API Documentation

To explore the API endpoints, visit the Swagger UI. You can access it at:

```
http://localhost:your_port_number/api-docs
```

You can also check the [Releases](https://github.com/joaovlmxs/sabat-MERN-GCP/releases) section for the latest updates and downloadable files.

## Deployment

This project is designed for easy deployment on Google Cloud Platform. Here’s a brief guide on how to deploy:

1. **Create a Google Cloud Project**

   Go to the [Google Cloud Console](https://console.cloud.google.com/) and create a new project.

2. **Enable App Engine**

   In the Google Cloud Console, enable App Engine for your project.

3. **Install Google Cloud SDK**

   Follow the instructions on the [Google Cloud SDK installation page](https://cloud.google.com/sdk/docs/install).

4. **Deploy the Application**

   Use the following command to deploy your application:

   ```bash
   gcloud app deploy
   ```

5. **Visit Your Application**

   Once deployed, you can visit your application at:

   ```
   https://your_project_id.appspot.com
   ```

## Contributing

We welcome contributions to this project. If you want to contribute, please follow these steps:

1. **Fork the Repository**

   Click on the "Fork" button at the top right of the repository page.

2. **Create a New Branch**

   Use the following command to create a new branch:

   ```bash
   git checkout -b your-feature-branch
   ```

3. **Make Your Changes**

   Make the necessary changes to the codebase.

4. **Commit Your Changes**

   Use the following command to commit your changes:

   ```bash
   git commit -m "Description of your changes"
   ```

5. **Push to Your Fork**

   Push your changes to your forked repository:

   ```bash
   git push origin your-feature-branch
   ```

6. **Create a Pull Request**

   Go to the original repository and click on "New Pull Request."

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Author**: João
- **Email**: joaovlmxs@example.com
- **GitHub**: [joaovlmxs](https://github.com/joaovlmxs)

Thank you for checking out the **sabat-MERN-GCP** repository! We hope you find it useful for your projects. Don't forget to check the [Releases](https://github.com/joaovlmxs/sabat-MERN-GCP/releases) for the latest updates.