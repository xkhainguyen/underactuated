FROM robotlocomotion/drake:jammy-20221116

RUN apt-get -q update && apt-get -q install -y --no-install-recommends nginx-light xvfb && apt-get -q clean

ENV DISPLAY=:1