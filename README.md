# finacial_text_classifier
using fastapi to wrap  up the codebase of  https://www.youtube.com/watch?v=i6qL3NqFjs4 


## how to run it ?

### fastapi
```
pip install -r requirements.txt
```

```
uvicorn uvicorn main:app --reload
```

### dockerize it at first
```
docker build -t localhost/finacial_text_classifier .
```

### docker run it
```
docker run -p 8000:8000 localhost/finacial_text_classifier
```

again , thanks for the pretty author of https://www.youtube.com/watch?v=i6qL3NqFjs4  :)


## references:
TF-IDF: https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/

fastapi: https://fastapi.tiangolo.com/

Docker:  https://fastapi.tiangolo.com/deployment/docker/
