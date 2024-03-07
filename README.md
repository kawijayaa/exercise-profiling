# Profiling Exercise

## Screenshots

```/all-student```
![all_student_gui](https://i.imgur.com/vDV9fdy.png)
![all_student_cli](https://i.imgur.com/xFpLjUo.png)

```/all-student-name```
![all_student_name_gui](https://i.imgur.com/pBgVmWC.png)
![all_student_name_cli](https://i.imgur.com/pdZifld.png)

```highest-gpa```
![highest_gpa_gui](https://i.imgur.com/q6Eb1t5.png)
![highest_gpa_cli](https://i.imgur.com/eiMlUo6.png)

## Reflection
1. JMeter can be useful if we want to test the overall performance of our application. IntelliJ Profiler can be useful if we want to track down what part of our application is taking the most time.
2. The profiling process can identify what functions or methods are taking the most time to execute. This can help us identify what part of our application that needs optimizing and/or refactoring.
3. Yes, because we can see how much time each function or method takes up in the overall execution time of our application.
4. The main challenge was understanding how to use the IntelliJ Profiler. I had to read the documentation and watch a few tutorials to understand how to use it.
5. The main benefits of IntelliJ Profiler besides the ability to track down what part of our application is taking the most time is that the result of the profiling is shown beside the code. This makes it easier to see what part of the code is taking the most time while we are reading the code.
6. The differing results between the IntelliJ Profiler and the JMeter could be due to the fact that the Profiler is monitoring the runtime and JMeter only tests the overall performance of the application.
7. For the optimization, I used the parallelStream() method to make the program run faster. I also used the IntelliJ Profiler to track down what part of the program is taking the most time and optimized that part of the program. To ensure that the program is still working as intended, I checked the results before and after the optimization since this application has no unit tests.