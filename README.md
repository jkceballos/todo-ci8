# Proyecto CI con Flask, Docker, GitHub Actions y Codecov

[![CI](https://github.com/jkceballos/todo-ci8/actions/workflows/ci.yml/badge.svg)](https://github.com/jkceballos/todo-ci8/actions)
[![codecov](https://codecov.io/gh/jkceballos/todo-ci8/branch/main/graph/badge.svg)](https://codecov.io/gh/jkceballos/todo-ci8)

## ¿Qué incluye este proyecto?

- API REST simple con Flask
- Tests automáticos con Pytest
- Dockerfile para contenerización
- CI con GitHub Actions
- Reportes de cobertura en Codecov

## Cómo probar localmente

```bash
docker build -t todo-ci8 .
docker run todo-ci8
