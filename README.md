# jmeter-tests

Sample JMeter test scripts to demonstrate easy parameterization through the help of properties file to adapt with multiple performance test scenarios

Pre-requistes: JMeter

Usage:
* Execute tests with peak hour scenario:

`jmeter -p PeakHourLoad.properties -n -t k6-performance-test.jmx`
