FROM docker.io/node:24-${templateOption:imageVariant}

LABEL org.opencontainers.image.source="https://github.com/outloudvi/devcontainer-templates"
LABEL org.opencontainers.image.description="Debian container with Gemini CLI installed"
LABEL org.opencontainers.image.licenses="MIT"

WORKDIR /workspace

RUN npm install -g @google/gemini-cli

ENTRYPOINT [ "/bin/bash" ]