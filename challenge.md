
# Lab 06 Challenge: Install It Yourself

## 1. Install and run htop
Command: sudo apt install -y htop
Run command: htop
Answer: htop displays CPU usage, memory usage, and running processes.

## 2. Apache2 package version
Command: apt show apache2 | head -4
Answer: The available apache2 version is 2.4.66-2ubuntu2.6.

## 3. Installed packages
Command: apt list --installed | wc -l
Answer: The command returned 734.

## 4. Run Alpine with Docker
Command: sudo docker run --rm alpine echo Hello from Alpine
Answer: Hello from Alpine

## 5. Docker configuration paths
Command: ls -l /etc/apt/keyrings/docker.asc
Command: ls -l /etc/apt/sources.list.d/docker.sources
Answer: The key is /etc/apt/keyrings/docker.asc and the sources file is /etc/apt/sources.list.d/docker.sources.

## 6. Remove htop
Command: sudo apt remove -y htop
Command: hash -r
Command: htop
Answer: The shell reports that htop is not found after removal.

