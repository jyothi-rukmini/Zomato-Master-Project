FROM node:alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .


ENV MONGO_URL=mongodb+srv://Jyothi:JyoRukN@36029@zomato-master.detgv.mongodb.net/zomato?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=1003012644722-2oun339u6rs18dip7pg7ub1659rn0e7q.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=O0_g9Do9pnRk9qvOQdmerVCY
ENV AWS_S3_ACCESS_KEY=AKIA2G4RARAPZOQ3EM2Y
ENV AWS_S3_SECRET_KEY=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
ENV MAILGUN__DOMAIN=sandboxa3f1525fde7b4010861fbd023a846811.mailgun.org
ENV MAILGUN__API__KEY=115906a25a9b2f5ca9c4f157c602d18f-9776af14-74561d92
ENV RZR_PAY_ID=rzp_test_RNvW44vJHiXg1b
ENV RZR_PAY_SECRET=MHdAwlbdqlCJlFW4kKrbk4kT
ENV NODE_ENV=production
ENV PORT=4000

CMD ["npm", "run", "start"]