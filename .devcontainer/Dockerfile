# syntax=docker/dockerfile:1

ARG VARIANT="20"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}

USER node
RUN npm install -g @sap/cds-dk
WORKDIR /home/node
