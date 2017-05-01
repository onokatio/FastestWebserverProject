FROM alpine:edge

RUN apk --no-cache --update add \
	nginx \
	&& mkdir -p /run/nginx

CMD ["nginx","-g","daemon off;"]
