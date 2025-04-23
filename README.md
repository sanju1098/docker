## 🚀 Docker Container Commands

| Command                                               | Purpose                                   |
|--------------------------------------------------------|--------------------------------------------|
| `docker build -t <docker-img> . `                     | Build a docker image  |
| `docker run -d -p 8080:80 <image>`                    | Run container in detached mode, map ports  |
| `docker run --name mycontainer -it <image> bash`      | Run interactively with terminal            |
| `docker ps`                                            | List running containers                    |
| `docker ps -a`                                         | List all containers (including stopped)    |
| `docker stop <container-id>`                          | Stop a running container                   |
| `docker start <container-id>`                         | Start a stopped container                  |
| `docker rm <container-id>`                            | Remove a container                         |

---

## 📁 Volumes & Logs

| Command                                               | Purpose                                |
|--------------------------------------------------------|-----------------------------------------|
| `docker logs <container-id>`                          | View logs from container                |
| `docker volume ls`                                    | List volumes                            |
| `docker volume rm <volume>`                           | Remove a volume                         |
| `docker exec -it <container-id> bash`                 | Access running container terminal       |

---

## 🛠️ Common Real-World Docker Commands

```bash
# Build the Docker image
docker build -t my-app .

# Run the container in detached mode and map ports
docker run -d -p 8080:80 my-app

# List running containers
docker ps

# View container logs
docker logs <container-id>

# Stop a running container
docker stop <container-id>

# Remove a container
docker rm <container-id>

