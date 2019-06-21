FROM scratch
RUN mkdir -p /app
COPY instrumented_app /app
WORKDIR /app
EXPOSE 8080 
ENTRYPOINT ["/instrumented_app"]

