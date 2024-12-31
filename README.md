# SciCat ESS Science Data Catalogue Docker Setup 🐳✨  

This repository provides a Dockerized setup for deploying the **SciCat Science Data Catalogue**, previously used at the **European Spallation Source (ESS)**. It has been **superseded by SciCat Live**, but remains as a reference for historical setups and deployments.

---

## Features ✨  

- **Dockerized Deployment**: Simplified deployment using Docker containers.  
- **Pre-configured Environment**: Includes MongoDB and necessary services for SciCat.  
- **Archived Reference**: Useful for understanding legacy SciCat setups.  

---

## Prerequisites 🛠️  

- **Docker** and **Docker Compose** installed.  

---

## Installation  

1. Clone the repository:  
git clone https://github.com/your-username/scicat-docker-setup.git  
cd scicat-docker-setup  

2. Start the Docker containers:  
docker-compose up -d  

3. Access the application in your browser:  
http://localhost:3000  

---

## Configuration  

1. Update the `.env` file to configure environment variables such as MongoDB credentials and SciCat settings.  

2. Restart the containers to apply changes:  
docker-compose down  
docker-compose up -d  

---

## File Structure 📂  

- `docker-compose.yml`: Defines the Docker services for SciCat and MongoDB.  
- `.env`: Environment variable configurations.  
- `README.md`: Documentation for this repository.  

---

## Status ⚠️  

This repository has been **superseded** by [SciCat Live](https://github.com/username/scicat-live). It is no longer actively maintained and exists solely for archival purposes.  

---

## Contributing 🤝  

Contributions are not actively accepted for this repository. Please direct efforts to the [SciCat Live repository](https://github.com/username/scicat-live).  

---

## License 📝  

This project is licensed under the MIT License. See the LICENSE file for details.  

---

**Legacy Docker setup for SciCat—refer to SciCat Live for the latest developments!** 🐳✨  
