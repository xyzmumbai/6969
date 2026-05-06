# Step 1: Use an official Python runtime as a parent image
FROM python:3.11-slim

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy the local script into the container at /app
COPY app.py .

# Step 4: Run the script when the container launches
CMD ["python", "app.py"]
