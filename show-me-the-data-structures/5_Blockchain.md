Blockchain
================

### Task
Code a blockchain, where each block has a code generated by a hashing function
and contains the hash of the immediate previous hash, together with data and
time stamp.

### Choices and reasoning

- The block has their on class, with automatically generated hash codes using the
data and time stamps.
- The chain is implemented using a linked list/ and separately an array.
- Implemented function to verity the whole change is consistent. Time complexity O(n_blocks), because
reproducing the hashes is O(1).
- Tested, including edge cases. 

### Complexity

- Big O, time complexity of creating a block depends on how hard is O(1). Mining would increase time complexity looking for a hash really hard to decode. The

- Big O, space complexity is the the size of the data plus the size of the hash generated, O(n).
