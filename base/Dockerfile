FROM busybox
RUN mkdir /root/demo
ENV VERSION 1.0
WORKDIR /root/demo
RUN touch file01.txt
RUN touch file-$VERSION.txt

CMD ["/bin/sh"]