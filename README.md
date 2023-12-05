# Random-User-API-Performance-Test
I conducted a load test as part of this project to evaluate performance on a demo server. Here, I have determined the actual TPS (throughput per second) and expected TPS using a load test on jmeter. Additionally, by running additional load tests on the same URL, I was able to identify the stress test point, or the point at which the system begins to display 1% error.

## URL
https://random-data-api.com/api/v2/users

## To Do
- To find actual TPS if 120000 user can give load for 12 hour
- To perform load test
- To find bottleneck/stress test point (At which point the system starts to show 1% error)

## Pre-requisite
- JDK 8 or 11 with JAVA_HOME setup
- JMeter with Jmeter_HOME setup

## How To Run This Project
- Clone this project
- put the jmx file the bin folder of the jmeter installation path
- open cmd and hit the following command jmeter
- from jmeter open the file from the bin and hit the run button

  ## LOAD Test
  ![Load Test](https://github.com/naoshin2111/Random-User-API-Performance-Test/assets/70252193/b223228a-4fc2-4520-adf9-e660594457da)
  ## STRESS Test
  ![Stress Test](https://github.com/naoshin2111/Random-User-API-Performance-Test/assets/70252193/b0acc456-339e-4cea-8ecd-1acfca55d9b8)
  ## Reports
  ![Reports](https://github.com/naoshin2111/Random-User-API-Performance-Test/assets/70252193/ab3d0367-c9b9-40ca-8777-9228265d7c66)
