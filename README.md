# Principais comandos Git:


To start the Ollama container, execute the following command:
```bash
docker run -d -p 11434:11434 --name Ollama ollama/ollama
```  

This command does the following:
docker run: Creates and runs a new container from an image.
"-d": Runs the container in "detached" mode (in the background).
"-p 11434:11434": Maps port 11434 of the container to port 11434 on your computer, allowing you to connect to the service.
"--name Ollama": Names the container "Ollama".
"ollama/ollama": Specifies the image to use to create the contain
