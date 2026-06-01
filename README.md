# MateIV_Transporte_Publico

## Uso

1. Clonar el repositorio.
2. Abrir la carpeta raíz del proyecto en VS Code.
3. Crear un entorno virtual de Python 3.12.
4. Instalar dependencias:

```bash
pip install -r requirements.txt
```

5. Seleccionar el kernel de ese entorno en el notebook.
6. Ejecutar `Run All`.

## Datos

Los archivos crudos usados por el notebook están en `datasets/`:

- `conectividad_aerea_cabotaje.csv`
- `conectividad_aerea_internacional.csv`
- `202512-informe-ministerio-actualizado-dic-final.csv`
- `202604-informe-ministerio.csv`
- `failbondi-2026-05-20-dump.json`

Los datasets son grandes y están configurados para subirse con Git LFS mediante `.gitattributes`.

## Nota

El notebook busca automáticamente la carpeta `datasets/` desde la ubicación actual hacia la raíz del proyecto. Por eso puede clonarse en cualquier ruta del equipo, siempre que se ejecute desde dentro del repositorio.
