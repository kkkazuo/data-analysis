# Build Image
```
docker build -t ktake-analysis .
```

# Start up
```
docker run -it -p 8888:8888 -v $(pwd)/analysis:/data --rm ktake-analysis
```
