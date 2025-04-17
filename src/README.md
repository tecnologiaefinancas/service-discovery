## Service Discovery

This repository serves as a **service discovery point** for some applications within this repository.

### Technologies Used
- **Spring Cloud Netflix Eureka** for service registration and discovery.

### Structure
- This repository contains the necessary configuration to run a Eureka server.
- Applications within the repository connect to this service discovery for registration and communication.

### How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/tecnologiaefinancas/service-discovery.git
   ```
2. Navigate to the project directory:
   ```bash
   cd service-discovery
   ```
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```
4. Ensure that other applications are configured to connect to the Eureka server.

5. It runs it in:
```bash
   http://localhost:8761/
  ```

