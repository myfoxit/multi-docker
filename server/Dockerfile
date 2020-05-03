FROM node:alpine


WORKDIR "/app"

# Copy dependencies
COPY ./package.json ./

# Install some dependencies
RUN npm install

COPY ./  ./

# Default command
CMD ["npm", "run", "start"]