# Online Experimentation: With Great Power Comes Great Responsibility
Lizzie (Eardley Senior Data Scientist Split)
Sophie (Harpur Product Manager Split)
https://www.split.io/


* Today teams are moving faster than ever
* MVP, iterations, small releases
* Despite moving faster, we still fail


* What is controlled experimentation
  * An experiment where everything is held constant except one variable
  * Removes external influences
  * Differences in metrics are due to what was changed
  * Can distinguish noise from real signal (statistically significant)
  * Can limit human biases


* Three stages of online controlled experimentation
  * Design
    * Hypothesis
      * Clear
      * Specific
      * Has a benchmark which is measurable
      * Expected impact
  * Metrics
    * Meaningful
      * Directly captures business value
      * Beware of using one metric
      * But also beware of using too many metrics
    * Sensitive
      * Detects small changes
    * Directional
      * positive and negative (better or worse)
    * Understandable
  * Power analysis
    * understanding the power of your experiment is vital
    * Any test will only be able to measure differences larger than a given size
    * Larger sample size can detect smaller changes
  * Execution
    * Randomization
    * Data collection
      * Make sure data is flowing and being collected
  * Analysis
    * Get your p-value
      * How likely is it that you'd see a difference as big as this if there were no real difference
      * Reject the null hypothesis
      * Less than 0.05 (95% sure its not due to noise)


* Don't peek - don't watch the experiment and stop it when you see results you like or don't like


* Takeaways
  * Confidence
  * Understanding
  * Know what your testing
  * Any well designed and implemented experiment is a successful experiment
