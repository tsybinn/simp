#FROM httpd:2.4



#RUN apt-get update  && apt-get install -y chrony openvpn easy-rsa nano mc
#
#RUN mkdir -p /etc/openvpn/keys  \
#    && mkdir /etc/openvpn/easy-rsa  \
#    && cd /etc/openvpn/easy-rsa \
#    && cp -r /usr/share/easy-rsa/* .



#ADD vars /etc/openvpn/easy-rsa
#WORKDIR /etc/openvpn/easy-rsa
#RUN bash
#
#LABEL maintainer="Kyle Manna <kyle@kylemanna.com>"
#
## Testing: pamtester
#RUN echo "http://dl-cdn.alpinelinux.org/alpine/edge/testing/" >> /etc/apk/repositories && \
#    apk add --update openvpn iptables bash easy-rsa openvpn-auth-pam google-authenticator pamtester libqrencode && \
#    ln -s /usr/share/easy-rsa/easyrsa /usr/local/bin && \
#    rm -rf /tmp/* /var/tmp/* /var/cache/apk/* /var/cache/distfiles/*