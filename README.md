# Document Management System

A robust document management system built with CodeIgniter 4, featuring document organization, version control, and user management.

## Features

- User Authentication and Authorization
- Document Upload and Management
- Version Control
- Document Categories and Tags
- Search Functionality
- Audit Trail
- Bulk Upload Support
- Error Handling and Logging

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Composer
- Node.js and npm (for frontend assets)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jacobrits1/doc_system.git
   cd doc_system
   ```

2. Install dependencies:
   ```bash
   composer install
   ```

3. Copy `.env.example` to `.env` and configure your environment:
   ```bash
   cp .env.example .env
   ```

4. Set up the database:
   ```bash
   php spark migrate
   ```

5. Start the development server:
   ```bash
   php spark serve
   ```

## Configuration

1. Database configuration in `.env`:
   ```env
   database.default.hostname = localhost
   database.default.database = doc_system
   database.default.username = your_username
   database.default.password = your_password
   ```

2. Email configuration in `.env`:
   ```env
   email.protocol = smtp
   email.SMTPHost = your_smtp_host
   email.SMTPUser = your_smtp_username
   email.SMTPPass = your_smtp_password
   ```

## Usage

1. Access the application at `http://localhost:8090`
2. Login with your credentials
3. Start managing your documents

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

MIT License