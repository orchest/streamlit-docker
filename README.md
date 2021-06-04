# Streamlit on Docker

## Run Streamlit
Run `docker build -t streamlit . && docker run -it -p 8501:8501 -v $PWD/src:/usr/src/app/src streamlit streamlit run src/main.py --logger.level=debug`

then open [localhost:8501](http://localhost:8501) in your browser.

Use the `STREAMLIT_SERVER_BASE_URL_PATH` environment variable to configure a custom base path.