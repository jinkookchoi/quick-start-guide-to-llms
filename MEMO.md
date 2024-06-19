docker build -f Dockerfile -t semantic-search-api .
docker run -it -p 8000:8000 semantic-search-api

