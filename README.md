# API Segura con FastAPI
Proyecto completo: microservicio REST con proteccion de credenciales e integracion LLM +
Notion.
## Instalacion y Puesta en Marcha
1. Clonar el repositorio:
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
cd TU_REPOSITORIO
2. Instalar dependencias:
pip install -r requirements.txt
3. Configurar variables de entorno:
cp .env.example .env
# Edita el archivo .env con tus claves locales
4. Iniciar el servidor:
python api_fastapi.py
5. Generar el calendario de dieta en Notion:
python dieta_llm_to_notion.py
