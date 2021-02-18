# Yellow
Yellow frontend and backend application for OpenDAX

## Develop
In this repo:

1. Run makefile
```
make asset
```
It will run build in the client folder and then all build files will be moved to public/assets.

2. Run go server
```
go run app.go serve
```

## Develop Client

1. Go to the client
```
cd client
```
2. Install dependencies
```
yarn install
```
3. Run app
```
yarn start
```

# Troubleshooting
**If it doesn't work and you see the white screen, check the order of the import files in index.html**
