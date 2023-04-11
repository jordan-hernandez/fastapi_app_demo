# Deploy ML models with FastAPI, Docker, and Railway

### 1. Develop and save the model with this Colab

[Open Colab](https://colab.research.google.com/drive/1uaALcaatvxOu42IhQA4r0bahfdpw-Z7v?usp=sharing)

### 2. Create Docker container

```bash
docker build -t app-name .

docker run -d -p 8080:80 app-name
```

### 3. Create Git repo

If you clone this repo this step is not needed. Or you can delete this git repo with `rm -rf .git` and start with a new one:

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
```

