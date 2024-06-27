# Azure AZ-204 Exam Study Notes

## Serverless Computing

Serverless computing, or Function as a Service (FAAS), is a microservice architecture run on the cloud. Key features include:

- Automatic scaling based on user demand
- Pay-as-you-go pricing model
- Stateless execution

### Disadvantages:
- Function timeout limit (configurable up to 10 min)
- 2.5 min timeout for HTTPS requests

## Azure Functions

Azure Functions utilize triggers and bindings:

### Triggers:
- Timer
- HTTP
- Blob
- Queue
- Event Hub
- Azure Cosmos DB

### Bindings:
- Input binding (provides input to the function)
- Output binding (stores the function's output)

## HTTP Trigger Authorization Levels

Azure Functions support three authorization levels for HTTP triggers:

- Function (requires function or host key)
- Anonymous (no authentication required)
- Admin (requires host key)

## Azure Storage

Azure Storage is Microsoft's cloud storage solution, offering:

- High availability
- Security
- Scalability
- Managed services for blobs, queues, and NoSQL data

### Azure Blob Storage

Azure Blob Storage is designed for storing unstructured data like files, logs, and multimedia content. Types include block blobs, append blobs, and page blobs.

## Durable Functions

Durable Functions extend Azure Functions to support stateful workflows, allowing for:

- Event-driven code execution
- Function chaining
- Orchestration and coordination of functions

### Function Types:
- Client function (entry point)
- Orchestrator function (workflow control)
- Activity function (unit of work)

## Azure App Service

Azure App Service hosts web applications and REST APIs, offering:

- Auto-scaling
- CI/CD support
- Deployment slots for testing and production environments

### App Service Plans
- Define compute resources (OS, region, VM size, pricing tier)
- Supports shared, dedicated, and isolated compute options

## Continuous Deployment (CD)

Azure App Service supports CD from:
- Azure DevOps
- GitHub
- Bitbucket

## Authentication and Authorization

Azure App Service provides built-in support for authentication and authorization, minimizing custom code requirements.

## Conclusion

These notes cover essential topics for the AZ-204 exam, focusing on serverless computing, Azure Functions, Azure Storage, Durable Functions, Azure App Service, and continuous deployment practices.

