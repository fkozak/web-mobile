1. Clone o repositório para sua máquina local:

    ```bash
    git clone https://github.com/fkozak/web-mobile.git
    ```

2. Acesse o diretório do projeto:

    ```bash
    cd web-mobile
    ```

3. Instale as dependências do projeto usando o pip:

    ```bash
    pip install -r requirements.txt
    ```

4. Crie o banco de dados PostgreSQL executando as migrações:

    ```bash
    python manage.py migrate
    ```

5. Inicie o servidor de desenvolvimento:

    ```bash
    python manage.py runserver
    ```
 
