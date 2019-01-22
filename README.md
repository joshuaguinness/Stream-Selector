# Stream-Selector
A python program which automatically allocates students into their second year engineering stream by free choice, then by GPA.

The program also does additional operations on the student data such as: finding the average GPA of male and female students, and sorting the students by GPA.

The program works by reading in data from three different textfiles, the student data, students who have free choice, and department capacity. It then allocates to their selected stream students who have free choie (High GPA from entering high school). After that, it allocates the rest of the students by GPA to either their first, second, or third choice of streams based on GPA.

I also created an automatic testing script, testCalc.py, which when runs, goes through 9 different test cases outputting whether they passed or not.

There is also automatic documentation generated via Doxygen. To see the documentation, type "make doc." I decided to push the PDF to the repo anyways.
 
## What I learned

Through this, I brushed up on my python from doing mostly C in the fall. I learned how to use dictionaries properly in python. A big thing I learned while doing this is the basics of how to automatically do testing by having test cases in a separate script then running that script. I had do think critically about the test cases I was running and their expected output, then call the different functions which read from different files.

I also am learning about how to properly document by code. For this I used Doxygen.
