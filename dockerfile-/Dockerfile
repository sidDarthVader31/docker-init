#dockerfile for app.sh
FROM ubuntu
COPY . /app
ARG curl_bin="curl"
RUN apt -y update && apt -y install $curl_bin
ENTRYPOINT ["/app/app.sh"]
CMD ["--argument"]

