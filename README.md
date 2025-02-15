# DevOps Project

This project demonstrates a DevOps workflow using:
- **Docker** for containerization.
- **Ansible** for automation.
- **AWS** for deployment.

## Project Structure
devops-project/
├── app.py # Flask web application
├── Dockerfile # Docker configuration
├── requirements.txt # Python dependencies
├── deploy.yml # Ansible playbook
├── inventory # Ansible inventory file
└── README.md # Project documentation

## How to Use
1. Clone this repository:
   git clone https://github.com/your-username/devops-project.git

2. Build the Docker image:
   docker build -t devops-flask-app .

3. Run the Docker container:
   docker run -d -p 5000:5000 devops-flask-app

4. Deploy to AWS using Ansible:
   ansible-playbook -i inventory deploy.yml
