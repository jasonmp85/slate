FROM alpine:3@sha256:d7342993700f8cd7aba8496c2d0e57be0666e80b4c441925fc6f9361fa81d10e

LABEL org.opencontainers.image.authors="Jason Petersen" \
      org.opencontainers.image.vendor="Jason Petersen" \
      org.opencontainers.image.url="https://github.com/jasonmp85/slate" \
      org.opencontainers.image.documentation="https://github.com/jasonmp85/slate/blob/master/README.md" \
      org.opencontainers.image.source="https://github.com/jasonmp85/slate" \
      org.opencontainers.image.licenses="MIT" \
      org.opencontainers.image.title="vimtutor" \
      org.opencontainers.image.description="Simple vimtutor for when it's missing"

RUN apk add --no-cache vim

ENTRYPOINT ["/usr/bin/vimtutor"]
