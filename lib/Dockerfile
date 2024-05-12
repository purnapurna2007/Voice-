FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/purnapurna2007/Voice/root/voice
WORKDIR /root/voice/
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
