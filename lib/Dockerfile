FROM quay.io/maherzubair/sigma-md:latest
RUN git clone https://github.com/Astropeda/Gnime-v2 /root/Astropeda/Gnime-v2
WORKDIR /root/Astropeda/Gnime-v2/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
 