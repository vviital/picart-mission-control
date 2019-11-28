# Motivation
This repo is a main entry point to the picart projects.

# How to run

To run services locally you have two options:
- Run in the stable mode (default);
- Run in the development mode. In the development mode you'll have in place code reload on the change mechanism.

## Stable mode
```bash
docker-compose up -d  --build
```

## Development mode
```bash
docker-compose -f docker-compose.dev.yml up -d  --build
```