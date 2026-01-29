FROM ghcr.io/hassio-addons/base:20.0.1

# Set shell
SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -fsSL https://opencode.ai/install | bash

EXPOSE 4096

CMD [ "opencode", "web" ]