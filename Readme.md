# About BentoPDF
BentoPDF container definition.

## Frameworks used
- BentoPDF

# Docker image details
Base image: bentopdf/bentopdf:latest
Exposed ports: 8080

# Deployment
## General
Service: bentopdf
Access URL: bentopdf.app.levell.ch

## Attached Networks
- traefik-public - access to reverse proxy

## Restart Policy
unless-stopped
