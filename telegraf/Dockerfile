FROM telegraf:1.13-alpine

RUN wget http://www.rtpro.yamaha.co.jp/RT/docs/mib/yamaha-private-mib.tar.gz &&\
    tar xvzf yamaha-private-mib.tar.gz -C /usr/share/snmp/mibs &&\
    rm yamaha-private-mib.tar.gz

