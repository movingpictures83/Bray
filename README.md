# Bray
# Language: R
# Input: CSV (network)
# Output: CSV (distances)
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: vegan_2.5.6

PluMA plugin that takes a community data matrix and computes the Bray-Curtis dissimilarity (Bray and Curtis, 1957) value between all samples.

Input should be provided as a CSV file with rows as samples and columns containing normalized abundances of every community member.
The plugin will then produce an output CSV file with rows and columns as samples, and entry (i, j) containing the Bray-Curtis dissimilarity
between sample i and sample j.
