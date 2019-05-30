### Info
Helps to pull npm packages and its recursive dependencies into an uploadable tarball 

### Make script executable
```
chmod +x npo.sh
```

### Help
```
./npo.sh -h
```

### Fetching all dependencies (including nested dependencies) from package.json
```
./npo.sh fetch --no-cache -p PATH_TO_PACKAGE.JSON
```

### Fetching dependencies (including nested dependencies) 
```
./npo.sh fetch --no-cache PACKAGE1 PACKAGE2 PACKAGE3
```

### Warning
node_modules folder is required, as some of the library files have been tweaked