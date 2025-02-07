<p align="center">
  <a href="https://affiliate.postiz.com">
    <img src="https://github.com/user-attachments/assets/af9f47b3-e20c-402b-bd11-02f39248d738" />
  </a>
</p>

<p align="center">
  <a href="https://postiz.com" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/765e9d72-3ee7-4a56-9d59-a2c9befe2311">
    <img alt="Postiz Logo" src="https://github.com/user-attachments/assets/f0d30d70-dddb-4142-8876-e9aa6ed1cb99" width="280"/>
  </picture>
  </a>
</p>

<p align="center">
<a href="https://opensource.org/licenses/Apache-2.0">
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License">
</a>
</p>

<div align="center">
  <strong>
  <h2>Your ultimate AI social media scheduling tool</h2><br />
  <a href="https://postiz.com">Postiz</a>: An alternative to: Buffer.com, Hypefury, Twitter Hunter, Etc...<br /><br />
  </strong>
  Postiz offers everything you need to manage your social media posts,<br />build an audience, capture leads, and grow your business.
</div>

## Intro

- Schedule all your social media posts (many AI features)
- Measure your work with analytics.
- Collaborate with other team members to exchange or buy posts.
- Invite your team members to collaborate, comment, and schedule posts.
- At the moment there is no difference between the hosted version to the self-hosted version.

## Tech Stack

- **NX (Monorepo)**
- **NextJS (React)**
- **NestJS**
- **Prisma (Default to PostgreSQL)**
- **Redis (BullMQ)**
- **Resend (email notifications)**

## Quick Start Guide for Windows

1. **Install Required Tools**:
    - **Git**: To manage the repository.
    - **Node.js**: For the frontend and backend dependencies.
    - **Python**: For running the backend server.
    - **Docker**: For managing containers (if needed).
    - **Visual Studio Code** or **your preferred code editor**.
  
2. **Clone the Repository**:
    Clone the forked repository:
    ```bash
    git clone https://github.com/your-username/postiz.git
    cd postiz
    ```

3. **Setup Python Virtual Environment for Backend**:
    Create a Python virtual environment for the backend:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate  # For Windows
    pip install -r requirements.txt  # Install required dependencies
    ```

4. **Install Node.js Dependencies for Frontend**:
    ```bash
    cd frontend
    npm install  # Install frontend dependencies
    ```

5. **Run the Project**:
    - Run the following command to start both the backend and frontend locally:
    ```bash
    powershell .\build.ps1 -rule "run"
    ```

This will automatically start the backend API server and the frontend React application.

6. **Access the Application**:
    - **Backend API** will be available at `http://localhost:8000` (adjust if needed).
    - **Frontend** will be available at `http://localhost:3000`.

## License

This repository's source code is available under the [Apache-2.0 license](LICENSE).

<br /><br /><br />

<p align="center">
  <a href="https://www.g2.com/products/postiz/take_survey" target="blank"><img alt="g2" src="https://github.com/user-attachments/assets/892cb74c-0b49-4589-b2f5-fbdbf7a98f66" /></a>
</p>
