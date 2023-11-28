FROM node:12.2.0-alpine
WORKDIR app
COPY . .
RUN npm install -g @angular/cli
CMD ["ng","build"]
CMD ["ng","new","Loginapp"]
EXPOSE 4200
CMD ["ng","serve"]
