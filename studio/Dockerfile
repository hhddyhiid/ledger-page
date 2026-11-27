FROM alpine:3.20
RUN apk add --no-cache ca-certificates tzdata
WORKDIR /srv
COPY site /srv/site
ENV PORT=8080
EXPOSE 8080
CMD ["/srv/site"]
