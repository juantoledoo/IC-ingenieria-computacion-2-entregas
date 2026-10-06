# Ingeniería en Computación II — Entregas

Repositorio para que cada grupo suba sus trabajos de la materia (UNRaf).

## Cómo entregar

`main` está protegida: nadie empuja directo, todo entra por **Pull Request**.

1. Hacé un **fork** de este repo (botón *Fork*, arriba a la derecha).
2. Cloná tu fork y creá una rama:
   ```bash
   git clone git@github.com:<tu-usuario>/IC-ingenieria-computacion-2-entregas.git
   cd IC-ingenieria-computacion-2-entregas
   git switch -c clase-N-apellido1-apellido2
   ```
3. Poné tu trabajo **solo dentro de la carpeta de tu grupo**:
   ```
   entregas/<apellido1>-<apellido2>/clase-N/
   ```
   Apellidos en minúscula, sin tildes, separados por guion (ej. `entregas/delbarco-sotelo/clase-2/`).
4. Commiteá, hacé push a tu fork y abrí un **Pull Request contra `main`** de este repo.
   En la descripción del PR poné los nombres completos de los integrantes.

Un PR que toque archivos fuera de la carpeta de tu grupo no se acepta.

## No subas

- Contraseñas, tokens ni credenciales (WiFi, MQTT, etc.): usá un `.env` y subí un `.env.example`.
- Entornos virtuales (`venv/`), `__pycache__/` ni archivos generados.
