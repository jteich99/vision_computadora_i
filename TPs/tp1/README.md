# TP1 - Vision por Computadora 1

Se utiliza el gestor de paquetes `uv`. Para crear el environment con `uv` debemos correr:
```shell
uv sync
```
Luego si queremos crear el Jupyter Kernel ejecutamos:
```shell
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=tp1
```