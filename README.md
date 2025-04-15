# sit737-2025-prac6p
1. Enable Kubernetes on Docker Desktop
•	Launch Docker Desktop from the system tray.
•	Navigate to the Settings panel.
•	Under the Kubernetes section, enable the Kubernetes option.
•	Apply the changes and allow Docker to restart for the configuration to take effect.
2. Application Development
•	Developed a basic Hello World application using NodeJS.
•	Create a Dockerfile 
3. Building the Docker Image
•	Use the Docker build command to build an image of the HelloWorld application from the Dockerfile.
•	Verify that the image has been created successfully and is listed locally
4. Uploading the Image to Docker Hub
•	Log in to Docker Hub.
•	Push the image to your Docker Hub repository for external accessibility,
5. Creating the Kubernetes Deployment
•	Define a deployment configuration file in the same folder to specify the container image.
6. Configuring the Kubernetes Service
•	Create a service configuration to expose the application externally.
7. Navigating to the Kubernetes Dashboard
•	Deploy the official Kubernetes Dashboard from the terminal using the command http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/
•	Create a dedicated service account for dashboard administration.
•	Bind this service account to the cluster-admin role using a role-binding configuration.
8. Accessing the Dashboard
•	Start the Kubernetes proxy to enable secure local access.
•	Open the Dashboard URL in a web browser.
•	Generate a login token for the admin-user service account.
•	Use the token to authenticate and access the Kubernetes Dashboard.
9. Accessing the website
•	Upload the Pod file and deployment file in the dashboard.
•	Confirm that the HelloWorld application is successfully running and accessible through the exposed service port.
•	Verify that the application status and deployment details are visible on the Kubernetes Dashboard.
10. Push Code to Repository
•	Initialize a Git repository (git init).
•	Add and commit files using the commands - git add . & git commit -m "Initial commit".
•	Push to a GitHub repository.
