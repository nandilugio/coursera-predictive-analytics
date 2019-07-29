Hipotesis testing
  2 groups
    Experimental: treatment
    Control: no treatment
  Hypoteses
    Types
      H[0]: Null hypotesis
        No difference between groups: observed difference is explicable by chance only
      H[A]: Alternative hypotesis
        Statistically significant difference between groups
    Errors
                 | Reject H[0] | Accept H[0] |
      -----------+-------------+-------------+
      H[0] true  | Ok (1-a)    | T2 err (a)  |
      H[0] false | T1 err (b)  | Ok (1-b)  <-+-- The power of the test: When there _is_ a difference, we fail to detect it only b x100% of the times
    Significance?
      p-value
        In repeated experiments (same sample size), how often you get results as extreme as this, assuming H[0]?
      
  Statistic (how "different" our groups are)
    Means
      t-test
    Vaiances
      F-test
  Experimental design
    Data collection
      Classical statistics
        Normally we collect the data ourselves
      Big-data thing
        We may have not have collected the data
    Selection of groups
      Randomized
        Assign individuals to groups at random
          No selection of any sort
      Blinded
        Participants don't know which group are they in
      Double-blinded
    

Confidence interfals
