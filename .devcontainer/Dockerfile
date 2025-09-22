FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

# Keep OS as small as possible; add only basic certs
RUN apt-get update && \
    apt-get install -y --no-install-recommends ca-certificates && \
    rm -rf /var/lib/apt/lists/*
