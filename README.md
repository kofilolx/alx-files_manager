# 0x04: File Manager API

## Overview

The File Manager API provides a simple interface for managing files, enabling users to perform the following operations:

- **Upload Files:** Upload files to the server.
- **Retrieve File Information:** Fetch metadata associated with uploaded files.
- **Download Files:** Download files from the server.
- **Share Files:** Share uploaded files with other users.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- MongoDB (version 4.0 or higher)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/ngugimuchangi/alx-files_manager.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd alx-files_manager
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

### Running the Application

1. **Start the Worker:**

   ```bash
   npm run start-worker
   ```

2. **Start the Express Server:**

   ```bash
   npm run start-server
   ```

## Environment Configuration

The following environment variables can be configured to customize the behavior of the Express server:

- `PORT`: Specify the port for the Express server (default: 3000).
- `DB_HOST`: Host address for the MongoDB server (default: localhost).
- `DB_PORT`: Port for the MongoDB server (default: 27017).
- `DB_DATABASE`: Name of the database to use (default: files_db).
- `FOLDER_PATH`: Absolute path to the folder where files will be stored (default: ./uploads).

## API Documentation

Comprehensive API documentation can be found [here](#).

## Testing

To ensure data integrity and avoid conflicts during testing, configure different `DB_DATABASE` and `FOLDER_PATH` environment variables when running tests.

### Running Tests

- **Run a Specific Test:**

   ```bash
   DB_DATABASE='test_database' FOLDER_PATH='/tmp/test_folder' npm test tests/testFile.js
   ```

- **Run All Tests:**

   ```bash
   DB_DATABASE='test_database' FOLDER_PATH='/tmp/test_folder' npm run test-all
   ```

## Authors

- [Kotey Jonathan](#)
```
