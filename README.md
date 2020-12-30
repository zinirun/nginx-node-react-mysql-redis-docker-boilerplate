# nginx-node-react-mysql-redis-docker-boilerplate
 docker-compose template of Node.js, React(Nginx), MySQL, and Redis

## Quick start
1. Clone this repo
    ```bash
    git clone https://github.com/zinirun/nginx-node-react-mysql-redis-docker-boilerplate.git
    ```
2. Move files to your completed project
   - `/client`: backend(Node.js)
   - `/server`: frontend(React to nginx)
   - `/mysql`: database(MySQL Initialization)
   - `.env`: environment file
   - `docker-compose.yaml`: docker-compose configuration
3. Do docker-compose up
   ```bash
   docker-compose up -d
   ```