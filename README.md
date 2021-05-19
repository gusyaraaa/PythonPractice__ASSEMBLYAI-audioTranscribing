# ASSEMBLYAI-audioTranscribing
Чтобы испытать готовое приложение на своём компьютере:
1. Загрузить материалы репозитория.
2. Открыть командную строку и перейти в папку с загруженными материалами.
3. Настроить и активировать виртуальное окружение.
4. Создать в папке с загруженными материалами файл .env и добавить в него ключ API(
    1. Открыть файл .env, который был создан ранее.
    2. Добавить в него следующее:
        API_TOKEN = "Your API Key"
    3. Строку Your API Key нужно заменить на ключ API, полученный на сайте AssemblyAI.)
5. Необходимые библиотеки нужно установить вручную (pip install streamlit, requests, python-dotenv или pip install -r requirements.txt)
6. Запустить приложение (streamlit run main.py)

Готовое приложение: https://share.streamlit.io/gusyaraaa/assemblyai-audiotranscribing/main/main.py
