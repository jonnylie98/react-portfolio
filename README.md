# My Portfolio

Responsive portfolio website 

## Built With

- React.js
- React Hooks
- Custom CSS
- Styled Components

## Using Docker

An additional Dockerfile has been added to the repo. If you wish to run the application via Docker:

```bash
# build docker image
docker build -t portfolio:latest .

# run docker container and portforward port 3000
docker run -d -p 3000:3000 portfolio:latest

# View the running container
Open up web browser and go to http://localhost:3000/
```

## Visit Project
https://jonnylie.netlify.app/

