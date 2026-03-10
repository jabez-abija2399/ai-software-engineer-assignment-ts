## How to run tests

### Locally
1. Install dependencies:
   ```bash
   npm install
   ```
2. Run tests:
   ```bash
   npm test
   ```

### With Docker
1. Build the Docker image:
   ```bash
   docker build -t assignment-tests .
   ```
2. Run the tests in the container:
   ```bash
   docker run assignment-tests
   ```
