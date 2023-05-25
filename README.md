# Capturama

## Installation
Follow below guide to setup and use the application.

**Note:** need to have symfony cli and composer are already installed.

1. Open and edit .env file. two important values should be changed: `DATABASE_URL`
2. Run below commands to install dependencies:
    ```bash
    $ composer install
    $
    ```


3. Run below commands in separated terminals:
    ```bash
    $ symfony server:start
    ```

4. Run below commands in separated terminals:
    ```bash
    $ docker compose up
    ```
   
5. Access the project API using `http://localhost:8000`

## Short description

create a user with console command bin/console user:create email@test.com

create an admin with console command bin/console user:create email@test.com --admin

to have access to users list