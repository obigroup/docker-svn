# Build:
```
docker build -t obigroup/svn .
```

# Run:
```
docker run --rm -ti obigroup/svn version
docker run --rm -v `pwd`:/src -ti obigroup/svn checkout URL[@REV]
```
