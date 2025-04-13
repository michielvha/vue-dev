FROM node:current-alpine3.21

# Install dependencies
RUN npm install -g @vue/cli

# Optional: install vite instead of vue-cli if you want that setup
# RUN npm install -g vite

WORKDIR /workspace

# Setup: install bash, git, etc. (if needed)
RUN apt-get update && apt-get install -y git bash