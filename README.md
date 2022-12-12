# Sampling Service:
Implement a stream sampling service in Python.

The /add endpoint of the service should accept a single integer number.

The /sample10 endpoint of the service should return an array with 10 numbers picked at random with equal probability from all numbers which have been added through the /add endpoint so far.

Whereas you're free to use any wide-spread web app framework (Flask, FastAPI, etc.), please provide your own implementation of the sampling logic.

Along with your implementation of the service, please supply a client script which would help demonstrating that the sampling logic is working.

Make sure we can run/test your solution using Docker.

What is the algorithmic and memory complexity of the /add and /sample10 endpoints? Suggest possible future improvements of your solution, especially for production cases with high loads.

Please make sure your solution is not publicly accessible, i.e., do not push it to a public Github repository or similar.