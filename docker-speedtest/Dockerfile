FROM stefanwalther/speedtest-exporter
ARG TARGETPLATFORM
ARG TARGETARCH
RUN echo "Target Platform ::: $TARGETPLATFORM"
RUN echo "Target Arch ::: $TARGETARCH"

CMD ["npm", "run", "start"]
# ARG OVERLAY_ARCH="amd64"

# FROM alpine
# ARG TARGETPLATFORM
# RUN echo "I am building for $TARGETPLATFORM"