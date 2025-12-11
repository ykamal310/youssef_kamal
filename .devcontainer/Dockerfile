FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update

RUN pip3 install flask

RUN apt-get install -y curl && \
    curl -fsSL https://deb.nodesource.com/setup_18.x | bash - && \
    apt-get install -y nodejs


RUN npm install -g @vue/cli
