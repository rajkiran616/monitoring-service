FROM sstarcher/sensu

COPY ./extensions /etc/sensu/extensions

RUN gem install influxdb

RUN /bin/install memory-checks network-checks disk-checks load-checks process-checks io-checks cpu-checks
