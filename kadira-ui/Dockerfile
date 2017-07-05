FROM jshimko/meteor-launchpad:latest

COPY ./ /app
ENV METEOR_ALLOW_SUPERUSER 1
RUN bash $METEORD_DIR/on_build.sh
