# Benchmarking
Benchmarking the API server for throughput, latency and errors.

There are multiple tools for this purpose. Out of which the popular ones are JMeter, Wrk, Apache Benchmark.


## Apache Bench
```ab -n 10000 -c 400 13.57.197.191:8080/```
![Apache Benchmark](ab.png)


## Wrk
```wrk -t12 -c400 -d30s http://13.57.197.191:8080```
![Wrk](wrk.png)


## JMeter
index.html
