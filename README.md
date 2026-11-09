# pediatric-t1d-secretion-bounds
A proof and reproducible analysis showing how the same six blood test results can fit both a rise and a fall in insulin production in children with type 1 diabetes.

# What six blood draws can tell us about insulin production

Researchers use C-peptide, a substance released alongside insulin, to track how much insulin the body makes. This project asks whether a two-hour test after a meal can tell if a child with type 1 diabetes made more or less insulin about a year later.

## What we found

We looked at 98 children and teens from the CLVer study. Each took a two-hour meal test at study entry and again at week 52. Each test included a fasting blood draw and five more draws after the meal.

The usual C-peptide score fell for 66 children. **For 21 of those 66, every reading fit two possible explanations.** In one, the child released less C-peptide over two hours at week 52. In the other, the child released more. Both explanations fit even when the rate of release had to change continuously and stay within limits.

## How the proof works

Think about two releases between blood draws. A larger release early on has more time to clear from the blood. A smaller release closer to the draw has less time to clear. Both can leave the same amount in the blood when the sample is taken.

The proof applies that idea to all six readings. It finds the range of total release that can explain them. We then build two sets of possible release patterns that match the readings for every child at both visits. One gives a drop in the group’s average total release. The other gives a rise.

The proof uses the same model of how C-peptide clears from the blood at both visits, assumes C-peptide levels were stable before the meal, and treats the reported readings as exact. A draw at minute 105 would give different readings for the two group reconstructions. That gives a future study a specific prediction to test.

The source of the data is the CLVer: Hybrid Closed Loop Therapy and Verapamil for Beta Cell Preservation in New Onset Type 1 Diabetes: A Proof-of-Concept Study, but the analyses, content and conclusions presented herein are solely the responsibility of the authors and have not been reviewed or approved by the Jaeb Center for Health Research.
