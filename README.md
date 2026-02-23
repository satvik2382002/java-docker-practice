
---

## 🏗️ What This Project Demonstrates

- Creating Docker images from Java applications
- Writing optimized Dockerfiles
- Using lightweight base images
- Managing containers, images, and networks
- Tagging and pushing images to Docker Hub

---

## 🚀 Build Image

```bash
docker build -t java-app .

docker run java-app    -to run

docker tag java-app your-dockerhub-username/java-app
docker push your-dockerhub-username/java-app

make sure you are logedin dockerhub.
