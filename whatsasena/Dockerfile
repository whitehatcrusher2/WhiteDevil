FROM KTBwhitedevil:latest

RUN git clone https://github.com/whitehatcrusher2/WhiteDevil /root/whitedevil
WORKDIR /root/whitedevil/ 
ENV KL=Kerala/India
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/whitehatcrusher2/White

CMD ["node","white", "bot.js"]
