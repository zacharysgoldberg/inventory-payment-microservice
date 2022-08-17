# Inventory-Microservice

## Design

FastAPI, React, Redis, and Docker

## Getting Started Locally

Install dependencies from one requirements.txt file, then run docker-compose yml file `docker compose up -d` from root directory.
Go to `localhost:3000/create` to create a new product. Open up a new browser tab to `localhost:3000/orders`. Enter newly created product ID including a quantity to purchase, and submit. Return to `localhost:3000`, wait a few seconds, refresh, and note the updated quantity for your product.