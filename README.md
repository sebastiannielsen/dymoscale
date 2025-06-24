# dymoscale
Simple HTML WebHID dymo scale reader for M-series and S-series of USB Dymo scales

This HTML and Javascript simply uses WebHID to read USB connected scales for Dymo.

The M and S scales handle weights a bit differently. The M-series weight in oz and grams and you can use the values directly, however, their oz values have a factor of 10.
The S-series weight in whole lbs or kgs, but they use a division factor of 10 when weighting in lbs.

The parameter "weird" in the function for setscale tells if the user is "weird" (uses non-scientific units) and corrects the display units for this.
