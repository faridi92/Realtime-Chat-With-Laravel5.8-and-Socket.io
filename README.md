# Realtime-Chat-With-Laravel5.8-and-Socket.io
This is a Realtime Chat Application made with Laravel5.8, Socket.io and Redis

Procedure to Install the repo

1. Clone the repo: git clone https://github.com/murad-faridi/Realtime-Chat-With-Laravel5.8-and-Socket.io.git Realtime
2. Enter to the destination folder : cd/Realtime
3. Install the composer : $composer install
4. Copy the .env.example to .env and configure the Database credentials for windows: copy .env.example .env for unix: cp .env.example .env
5. Generate the key : php artisan key:generate
6. Run the App by Starting development server: php artisan serve 
7. Install the reqruired dependencies in the exact order respectivly 

NPM: npm install

Redis: npm install redis --save-dev

ioRedis: npm install ioredis --save-dev

VueSocket.io: npm install vue-socket.io --save-dev

PRedis: composer require Predis/Predis

Socket.io: npm install socket.io --save-dev

8. Run NPM development: npm run dev
9. Start the redis Server: node server.js
10. Enjoy the APP
