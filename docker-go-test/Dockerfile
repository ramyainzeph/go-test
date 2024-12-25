# Use the official Go image as the base
FROM golang:1.20-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the Go script into the container
COPY main.go /app/main.go

# Run the Go script when the container starts
CMD ["go", "run", "/app/main.go"]
