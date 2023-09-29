# Use Python 3.6 or later as a base image
FROM python:3.8

# Copy contents into image
COPY . .

# Install pip dependencies from requirements
RUN pip install -r requirements.txt

# Set YOUR_NAME environment variable
env YOUR_NAME name1

# Expose the correct port
expose 5500

# Create an entrypoint
entrypoint ["python", "app.py"]
