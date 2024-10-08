Secure Backend Service for MediaMarktSaturn

**Objective:** Develop a backend service for managing security-related data that integrates with MediaMarktSaturn's systems. The service should be scalable, secure, and deployable on a cloud platform using Kubernetes.

**Requirements:**

- Implement the backend service using Python.
- Design and implement RESTful APIs for managing security-related data.
- Integrate the service with a mock authorization provider.
- Ensure the solution is cloud-agnostic and can be deployed on any major cloud provider (AWS, Google Cloud, Azure).
- Use Docker and Kubernetes for containerization and orchestration.
- Implement automated tests for the APIs.
- Document the project, including setup, deployment instructions, and API documentation.

**Tasks:**

**Project Setup:**

1. Create a new GitHub repository for the project.
2. Set up a Python project with necessary dependencies.
3. Initialize Docker and Kubernetes configurations.

**API Development:**

1. Design and implement RESTful APIs for the following operations:
    - Create a new security record.
    - Retrieve security information by ID.
    - Update security information.
    - Delete a security record.
    - List all security records.
2. Ensure proper validation and error handling for all endpoints.

**Authorization Integration:**

1. Implement a mock authorization service to simulate the integration.
2. Secure the APIs using token-based authentication (OAuth 2.0).
3. Ensure that each API request is authenticated and authorized using tokens from the mock authorization provider.

**Database Management:**

1. Choose a suitable database (SQL or NoSQL) for storing security data.
2. Implement database models and data access layers.
3. Optimize database queries for performance.

**Containerization and Orchestration:**

1. Write Dockerfile(s) to containerize the application.
2. Create Kubernetes deployment and service files for the application.
3. Ensure the application can be deployed on a cloud provider's Kubernetes service (e.g., AKS, GKE, EKS).

**Testing:**

1. Write unit and integration tests for the APIs.
2. Set up a CI/CD pipeline using GitHub Actions to run tests and deploy the application to a Kubernetes cluster.

**Documentation:**

1. Create a README file with project description, setup instructions, and usage guide.
2. Document the API endpoints using tools like Swagger or Postman.
3. Provide detailed deployment instructions for deploying the application on a cloud provider.

**Code Review and Submission:**

1. Push the code to the GitHub repository.
2. Ensure the repository is public or share access with the reviewer.
3. Submit the GitHub repository link along with any necessary credentials for accessing the deployed application.

**Evaluation Criteria:**

1. **Code Quality:** Clean, readable, and well-documented code.
2. **API Design:** Efficient and scalable API design with proper validation and error handling.
3. **Security:** Proper implementation of authentication and authorization.
4. **Cloud Deployment:** Successful deployment on a cloud provider using Kubernetes.
5. **Testing:** Comprehensive unit and integration tests.
6. **Documentation:** Clear and thorough project and API documentation.

**Submission Instructions:**

1. Fork the repository and create a branch named `develop`.
2. Complete the project as per the requirements.
3. Push the code to your GitHub repository.
4. Create a pull request to merge your `develop` branch into the `main` branch.
5. Submit the pull request link along with any relevant deployment credentials to **[your email/contact]**.

**Project Deadline:**

The project must be completed and the pull request submitted by **[deadline date]**.
