# Use an official Python runtime as a parent image
FROM python:3.8-slim

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 3838 available to the world outside this container
EXPOSE 3838

# When you run the Docker container, pass the DATABASE_URL as an environment variable:

# Run app.py when the container launches
CMD ["python", "app.py"]
