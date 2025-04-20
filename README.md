backend microservice system for job application management.  
Includes a .NET Core API, a Go consumer service, and RabbitMQ as the message broker.


JobAppSystem/                  ← repo หลัก
├── docker-compose.yml         ← รวมทุก service
├── README.md                  ← อธิบาย system + link service
├── .gitignore

git clone https://github.com/yourusername/JobAppSystem.git
cd JobAppSystem
docker-compose up --build

Then:

RabbitMQ UI: http://localhost:15672

.NET API Swagger: http://localhost:5000/swagger

Go Consumer logs: docker logs -f job-consumer


https://github.com/tanathon-101/JobApplicationTrackerAPI
https://github.com/tanathon-101/job-application-consumer-go
