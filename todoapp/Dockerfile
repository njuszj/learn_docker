FROM node
MAINTAINER njuszj@qq.com
RUN git clone -q https://github.com/docker-in-practice/todo.git
WORKDIR todo
RUN npm install
EXPOSE 8000
CMD ["npm","start"]

