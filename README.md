![reservei](https://github.com/luisbelisario/reservei-central-repo/assets/48885341/3759506c-637b-48bb-ab5e-c026ba5f3aae)


# Reservei System

This project aims to be a system to facilitate the reservation of sports courts for tennis, indoor soccer, beach volleyball and beach tennis. In it, customers will be able to register and view the courts they like the most, after which they will be able to reserve them and make the reservation payment directly through the application.

## Live project:

https://reservei-frontend-web.vercel.app/

## Project architecture:

The project will follow the microservices architecture and will be modularized as follows: a customer service will be responsible for registering users and sports court administrators, a court service that will be a catalog of courts available for reservation, a reservations that will only be responsible for managing the reservations made by customers on the courts and an application and a payment service that will only receive information from the reservation service (using Kafka for the messaging service). The access to the services will be controlled by a security API that will have the function of controlling access by logged in users and generating jwt tokens that allow access.

## Current status:

The integration between the client api and the security api was completed. The project is in the integration testing phase with the frontend to check for any failures or inconsistencies.

## Articles about the project:

Throughout the project I will post articles about the features developed, difficulties faced in the project and how to solve them. The articles are in the links below:

### Doing validations in an elegant and scalable way with SOLID principles: 

https://luisbls197.medium.com/doing-validations-in-an-elegant-and-scalable-way-with-solid-principles-ac530657723c

### Using OpenFeign for API communication in a microsservice environment:

https://luisbls197.medium.com/using-openfeign-for-api-communication-in-a-microsservice-environment-b6a667c8184

### Tutorial Spring Security:

https://www.youtube.com/watch?v=5w-YCcOjPD0&t=2330s

