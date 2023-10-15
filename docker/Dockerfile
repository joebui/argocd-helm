FROM nginx:stable-alpine-slim

COPY nginx.conf /etc/nginx/conf.d/service.conf

RUN ls -lh /etc/nginx/conf.d

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
