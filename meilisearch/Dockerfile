FROM getmeili/meilisearch:v1.29

HEALTHCHECK --interval=30s --timeout=10s --start-period=60s --retries=5 \
  CMD wget --no-verbose --spider http://127.0.0.1:7700/health || exit 1