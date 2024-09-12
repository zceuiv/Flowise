FROM flowise:local

RUN npm install -g pnpm
RUN pnpm config set store-dir /root/.local/share/pnpm/store

RUN apk add --no-cache bash

# docker build -t flowise-dev:local .