ARG BUILD_FROM=ghcr.io/hassio-addons/base:13.1.4
FROM ${BUILD_FROM}

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

ARG BUILD_FROM=ghcr.io/hassio-addons/base:13.1.4
FROM ${BUILD_FROM}

RUN apk add --no-cache util-linux

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
