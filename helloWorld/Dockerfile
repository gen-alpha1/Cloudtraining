# Use the official Python image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the Python script into the container
COPY hello.py welcome.py .

# Run the Python script when the container launches
CMD ["python", "./hello.py"]

# Run the python script when the container launches
CMD ["python", "./welcome.py"]

# Run both Python scripts and print their outputs when the container launches
CMD ["sh", "-c", "python ./hello.py > output.txt && python ./welcome.py >> output.txt && cat output.txt"]
