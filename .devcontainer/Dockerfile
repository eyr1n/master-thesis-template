FROM mcr.microsoft.com/devcontainers/base:trixie

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y \
        texlive-full \
        python3-pygments \
        inkscape \
    && rm -rf /var/lib/apt/lists/*
