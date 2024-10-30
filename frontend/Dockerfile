# Use the official Node.js image with version 20
FROM node:20.10.0

# Set the working directory inside the container
WORKDIR /app

# Copy the rest of the application files
COPY . .

# Install the dependencies
RUN npm install --force



# Build the React application
RUN npm run build

# Expose the port that the application will run on
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
