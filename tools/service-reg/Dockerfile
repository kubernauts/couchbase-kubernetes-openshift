FROM node:argon
RUN mkdir -p /opt/service-reg
WORKDIR /opt/service-reg
COPY . /opt/service-reg
RUN npm install
EXPOSE 3000
CMD ["echo hello"]
