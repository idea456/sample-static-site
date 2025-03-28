FROM public.ecr.aws/nginx/nginx:stable-perl

COPY index.html /usr/share/nginx/html/

RUN ls

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
