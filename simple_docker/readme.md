example image build command 
```docker build -t test:latest .```
-t = Name and optionally a tag in the 'name:tag' format

example run command to run image that we build
```docker run -p 5000:5000 -d test:latest```
-p = Publish a container's port(s) to the host
-d = Run container in background and print container ID