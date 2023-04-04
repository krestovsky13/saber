### Local launch of the project
```
git clone https://github.com/krestovsky13/Saver

docker build -t <image_name> -f Dockerfile .  
docker run --publish 8000:8000 --name <container_name> <image_name>

### Tests:
docker exec -it saber_cont sh
cd src/tests
pytest
```
