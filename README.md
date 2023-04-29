# Anagrams: Performance Comparison of Different Approaches in Google Chrome

In this study, the performance of four different approaches to identify anagrams in Google Chrome was analyzed:

1. Using an Object (areAnagrams1)
2. Using a Map (areAnagrams2)
3. Using a limited array (areAnagrams3)
4. Using a regular array (areAnagrams4)

## Results

The results obtained for each approach:

- Object: 105.4 ms
- Map: 28 ms
- Limited Array: 5.5 ms
- Array: 6.9 ms

## Conclusions

Based on the research results, the following conclusions can be drawn:

1. **Limited array** (areAnagrams3) proved to be the fastest approach, taking only 5.5 ms.
2. **Regular array** (areAnagrams4) showed slightly worse results, taking 6.9 ms.
3. **Map** (areAnagrams2) came in third place with an execution time of 28 ms.
4. **Object** (areAnagrams1) showed the worst result, taking 105.4 ms.

Thus, to identify anagrams with the highest performance in Google Chrome, it is recommended to use the limited array approach (areAnagrams3).
