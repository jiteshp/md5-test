# md5-test
Tests two MD5 implementations (by Paul Johnston &amp; Joseph Meyers) for speed.

## The test
The test assumes that Joseph's implementation is faster than Pauls, based on http://www.myersdaily.org/joseph/javascript/md5-text.html.

1. Run both the MD5 functions for 1, 10, 100, 1000, 10000 &amp; 100000 iterations.
2. Calculate the time required in milliseconds for each iteration.
3. Calculate the average time required for both implementations.

## The results
Note that the results will vary based on the computer & browser you are using. These were the results on my computer using the Chrome browser.

```
Iterations: 1
Average time for Paul's script: 0
Average time for Josephs's script: 0
Josephs's script is NaN% faster

Iterations: 10
Average time for Paul's script: 1.7
Average time for Josephs's script: 0.1
Josephs's script is 94.11764705882352% faster

Iterations: 100
Average time for Paul's script: 0.22
Average time for Josephs's script: 0.02
Josephs's script is 90.9090909090909% faster

Iterations: 1000
Average time for Paul's script: 0.044
Average time for Josephs's script: 0.021
Josephs's script is 52.27272727272727% faster

Iterations: 10000
Average time for Paul's script: 0.018
Average time for Josephs's script: 0.0086
Josephs's script is 52.22222222222223% faster

Iterations: 100000
Average time for Paul's script: 0.01603
Average time for Josephs's script: 0.00636
Josephs's script is 60.3243917654398% faster
```
