#NodeJS sample application with Dockerfile

```
  git clone git@github.com:vijaymali1990/poc-nodejs.git
  cd poc-nodejs

  docker build -t nodejs_app .
  docker run -d --publish 3000:5000 nodejs_app

```

## Visit the http://localhost:3000/
