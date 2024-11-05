# 💍 University Community Marriage Platform Backend (WIP)

This backend service is designed to support a platform that helps Shi'a students at our university connect with potential spouses in a safe and respectful environment.

## 🚀 Features

- **Profile Creation**: Enables users to create and manage their profiles.
- **User Authentication**: Provides secure sign-up and login mechanisms.
- **Connection Requests**: Allows users to request contact information with mutual consent.

## ⚙️ Technologies Used

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Axum-3A3A3A?style=for-the-badge&logo=rust&logoColor=white" alt="Axum">
  <img src="https://img.shields.io/badge/SQLx-477999?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQLx">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

### Backend Stack

- **Rust**: A safe, concurrent, and practical language.
- **Axum**: A web framework that focuses on ergonomics and modularity.
- **SQLx**: An async SQL toolkit for Rust.
  
### Database

- **PostgreSQL**: A powerful, open-source relational database system.

## 📦 Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) installed on your machine.
- [PostgreSQL](https://www.postgresql.org/download/) installed and running.

### Clone the Repository

```zsh
git clone https://github.com/smarizvi110/marriage_platform_backend.git
cd marriage_platform_backend
```

### Backend Setup
1. Create a `.env` file in the root directory using the provided [`.env.example`](.env.example) as a template:
  ```zsh
  cp .env.example .env
  ```
2. Update the `.env` file with your PostgreSQL database credentials.
3. Run the migrations:
  ```zsh
  cargo sqlx migrate run
  ```
4. Start the backend server:
  ```zsh
  cargo run
  ```

## License
THis project is licensed under the EUPL 1.2 license - see the [LICENSE](LICENSE) file for details.
