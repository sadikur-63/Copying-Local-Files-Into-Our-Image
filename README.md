# Copying Local Files Into my Image

This project demonstrates how to copy local files (such as custom HTML pages) into a Docker image using a `Dockerfile` and Nginx 1.27.0.
## Project Structure
```text
dockerfile-nginx/
├── Dockerfile      # Docker configuration instructions
├── index.html      # Custom webpage content
└── README.md       # Project documentation
docker build -t web_server_image . (Build the Docker Image)
docker run -d -p 80:80 web_server_image (Run the Container)
curl.exe http://localhost(test and Verify)
