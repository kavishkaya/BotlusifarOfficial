FROM lkruwan/botlusifar:new

RUN git clone https://github.com/kavishkaya/BotlusifarOfficial /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/kavishkaya/uploads
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit



CMD ["node", "bot.js"]
