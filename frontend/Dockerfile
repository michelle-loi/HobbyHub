# frontend latest node or we can set specific version of node
FROM node:latest

# Create app directory
WORKDIR /app

# Install app dependencies to workdir
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

EXPOSE 3000

# Run the app
CMD ["npm", "start"]

