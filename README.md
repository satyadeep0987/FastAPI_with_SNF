# FastAPI_with_SNF

1. Creating Virtual Env on Mac:

    * Creating a virtual env for your prject or for practice is a best practice a while going forward we are  going to install various packages which we might not reqire for all our project and installing directly into the machine is not good as they migh affect the loacl system. So better to have a local machine and do all your **Experiments**.

    * Check whether python is install or not:
        ```python
        python3 --version
        ```

        If not, then download and install it from below link:

        [Python Download](https://www.python.org/downloads/)

    * Checking PIP is there or not:

        ```python
        pip3 --version
        ```
    * Installing **virtaulenv**

        ```python
        pip3 install virtualenv
        ```
    * Creating a Virtual Environment:

        ```python
        python3 -m venv Virtual_Env
        ```

    * Activating Virtual Environment

        ```python
        source Virtual_Env/bin/activate
        ```

2. Installing FastAPI library and other dependancy into virtual env:

    ```python
        pip install fastapi
    ```

    For server:

    ```pyhton
        pip install "uvicorn[standard]"
    ```

    For snowflake connection:

    ```pyhton
        pip install snowflake-connector-python
    ```

    Other required dependency:
    ```python
        pip install sqlalchemy
        pip install databases 
    ```