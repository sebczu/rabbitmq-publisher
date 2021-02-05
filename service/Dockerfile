FROM rabbitmq:3.8.9-management

COPY /init.sh /init.sh
RUN chmod 777 /init.sh

RUN mkdir rabbitmq_events

CMD ["/init.sh"]