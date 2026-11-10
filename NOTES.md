# Docker Get Started: Node.js

## Guide
Containerize a Node.js application (https://docs.docker.com/guides/nodejs/)

## Langkah yang dikerjakan
1. Clone sample app docker-nodejs-sample
2. Jalankan `docker init` (Node, npm, start command `node src/index.js`, port 3000)
3. Build dan jalankan dengan `docker compose up --build`
4. Verifikasi aplikasi di http://localhost:3000

## Perintah penting
- `docker compose up --build`: build image dan jalankan container
- `docker compose down`: hentikan dan hapus container
- `docker images`: lihat image hasil build
- `docker ps`: lihat container yang berjalan
