# service-traefik
A docker-compose configuration for [traefik](traefik.io) service

## Running

1. Clone the repository
    ```shell
    git clone https://github.com/groupsky/service-traefik.git
    cd service-traefik
    ```

2. Configure 
    ```shell
    copy example.env .env
    editor .env
    ```

3. Start
    ```shell
    docker-compose up -d
    docker-compose logs -f
    ```

4. Test by opening the whoami service [whoami.example.com]
