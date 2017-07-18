# M101JS
M101JS: MongoDB for Node.js Developers

Hello! This repo contains my final project for this MongoDB course.

Some learning points:

1. Difference between updateOne() and findOneAndUpdate():
  - updateOne() returns UPDATE execution stats
  - findOneAndUpdate() returns original/updated object
  
  This is crucial to tweak callback functions.

2. Assert.equal(null, err):
  - This is a test to check if returned error (err) is non-existent (null)
  - If not equal, an error will be thrown

3. It may or may not be necessary to store the cursor in a variable.
  - Often, you can do operations directly tagging callback functions.


Thanks for reading! Hope you enjoyed.


Marc
