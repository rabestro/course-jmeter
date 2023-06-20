# course-jmeter
JMeter: Performance and Load Testing

```shell
rm -rf reports && \
~/bin/apache-jmeter-5.5/bin/jmeter.sh \
  -n -t src/landonhotel-load-test.jmx \
  -l reports/landonhotel-load-test.jtl \
  -e -o reports
```
