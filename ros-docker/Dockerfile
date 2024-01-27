
FROM ros:humble

# Install dependencies
RUN apt-get update && apt-get install -y \
    vim \
    && rm -rf /var/lib/apt/lists/*

COPY ./config/conf.ymal /src/config/conf.ymal