# Use the official Debian-based dev container base image
FROM mcr.microsoft.com/devcontainers/base:debian

# Install Neovim, Node.js, npm, and other useful packages
RUN apt-get update && apt-get install -y \
    neovim \
    nodejs \
    npm \
    curl \
    git \
    ca-certificates \
    && apt-get clean

# Install Wrangler globally for Cloudflare development
RUN npm install -g wrangler
