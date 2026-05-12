#use aws public image
FROM public.ecr.aws/docker/library/node:slim

#copy application code.
COPY . /app/

#change the working directory 
WORKDIR /app

#Install dependencies
RUN npm install

#start the express app
CMD ["node", "server.js"]