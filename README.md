# DjangoDocker

## Run in Docker Container (localhost:8000)

```console
docker-compose up
```

## Install (Mac)

```console
python -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
```

## Run Local Dev Server

```console
python app/manage.py runserver
```

## Format

```console
black .
```

## Add to Requirements

```console
pip freeze > requirements.txt
```
