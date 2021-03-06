# Data Structures and Algorithms


Data Structures and Algorithms (DSA) is one of the most important topic in computer science that every CS student must be proficient in and even non-CS students must have basic understanding of it. It is said that DSA is like bread and butter, necessity of CS. This repository is made for those students (like me :sunglasses:) who are eager to learn and want to implement data structures and algorithms.

### Why Go/GoLang and not C, C++ or Java?

I wouldn't disagree that C, C++ or Java wouldn't be a great language to implement DSA as one has to take care of lot things while writing the code like memory allocations and proper deallocations and by doing so one learns a lot.

However the reason why go would also be a good language to implement DSA is that it lacks a lot of magic. There is no operator overloading, so no way to hide extra complexity. An index operation is O(1), a loop is O(n) - always. There are no generics, so a lot of extra abstractions and helpers don't exist, which is actually pretty great. There is no laziness or other compiler-driven magic that might alter the runtime of your algorithms significantly. And Go has pointer and low-level primitives for slices, meaning it is apparent when data is packed or when data has an extra indirection. _In short_: Go make the actual algorithmic execution obvious from the code, which is a good thing to learn algorithms.

**Conclusion**: Go would also be a good language to get started with implementing Data Structures and Algorithms. :computer:

### Instructions

1. To get started make sure that you have go programming language installed on your computer. Follow how to install instructions from [golang download instructions](https://golang.org/doc/install).
2. Once go is installed on your machine, just clone or download this repository.
3. Now `cd <folder-name>` into the folder where the file you want to run is located.
4. Now run `go run .`.

### Example

Let's assume that you want to run files located in `graphs/directed_unweighted` directory then the syntax to run it would be:

```
cd graphs/directed_unweighted/

go run .
```

### FOLDER NAMES

1.  **algorithms** -
    - _01knapsack_dp_ - 0-1 Knapsack Problem using Dynamic Programming
    - _a_star_ -
      - _8_puzzle_ - 8 Puzzle problem using A<sup>\*</sup> Algorithm
      - _directed_graph_ - A<sup>\*</sup>&nbsp; Algorithm for directed graph
      - _undirected_graph_ - A<sup>\*</sup>&nbsp; Algorithm for undirected graph
    - _activity_selection_gp_ - Activity Selection using Greedy Programming
    - _assembly_line_scheduling_ - Assembly Line Scheduling algorithm using Dynamic Programming
    - _binary_reflected_gray_codes_ - Binary Reflected Gray Codes
    - _closest_pair_problem_ -
      - _cpp_brute_force_ - Closest Pair Problem using Brute Force Technique
      - _cpp_divide_conquer_ - Closest Pair Problem using Divide and Conquer Techinque
    - _combinations_ -
      - _with_r_ - With repetition of elements
      - _without_r_ - Without repetition of elements
    - _convex_hull_ -
      - _ch_brute_force_ - Convex Hull Algorithm using Brute Force Technique
      - _ch_divide_conquer_ - Convex Hull Algorithm using Divide and Conquer Technique
    - _expression_conversions_ -
      - _infix_postfix_ - Infix to Postfix Conversion
      - _infix_prefix_ - Infix to Prefix Conversion
      - _postfix_infix_ - Postfix to Infix Conversion
      - _postfix_prefix_ - Postfix to Prefix Conversion
      - _prefix_infix_ - Prefix to Infix Conversion
      - _prefix_postfix_ - Prefix to Postfix Conversion
    - _gcd_ - Greatest Common Divisor (Euclid's Algorithm)
    - _graphs_ -
      - _articulation_point_detection_ - Detecting Articulation Points in an undirected graph
      - _bellman_ford_ - Bellman Ford Algorithm
      - _bridge_detection_ - Bridge Detection/Cut Edge Detection in an undirected graph
      - _dijkstra_ - Dijkstra's Algorithm
      - _floyd_warshall_ - Floyd Warshall Algorithm (All points shortest path)
      - _kruskals_ - Kruskal's Algorithm (Finding Minimum Spanning Tree MST using Greedy Approach)
      - _prims_ - Prim's Algorithm (Finding Minimum Spanning Tree MST using Greedy Approach)
      - _topological_sort_ - Topological Sort
      - _traversals_ -
        - _cd_directed_graph_traversals_ - Cycle Detection in Directed Graphs using Traversals techniques
        - _cd_undirected_graph_traversals_ - Cycle Detection in Undirected Graphs using Traversals techniques
      - _tsp_ -
        - _tsp_dynamic_ -
          1. _directed_graph_ - TSP (Travelling Salesman Problem) using Dynamic approach for directed graph
          2. _undirected_graph_ - TSP (Travelling Salesman Problem) using Dynamic approach for undirected graph
        - _tsp_naive_ -
          1. _directed_graph_ - TSP (Travelling Salesman Problem) using Naive approach for directed graph
          2. _undirected_graph_ - TSP (Travelling Salesman Problem) using Naive approach for undirected graph
      - _union_find_ - Union Find / Disjoint Sets (Detecting cycles in an undirected graph)
    - _huffman_codes_ - Huffman Codes (Generating Huffman Codes)
    - _job_scheduling_gp_ - Job Scheduling Algorithm using Greedy Programming
    - _lcm_ - Least Common Multiple (using GCD Euclid's Algorithm)
    - _lcs_ - Longest Common Subsequence
      - _iterative_dp_ - Longest Common Subsequence using Dynamic Programming (Iterative Version)
    - _lo_permutations_ - Lexicographic Ordering Permutations
    - _longest_palindrome_substring_ -
      - _brute_force_ - Longest Palindrome Substring using Brute Force Technique
      - _manchers_ - Longest Palindrome Substring using Mancher's Algorithm
    - _making_change_dp_ - Making Change Problem using Dynamic Programming
    - _order_statistics_ - Finding Kth Smallest/Largest element (Order Statistics)
      - _naive_approach_ - Naive Approach using Max Heap - O(k + (n-k)\*log(k))
      - _quick_select_ - Quick Select (Quick Sort) - O(n^2), Θ(nlogn)
      - _worst_case_linear_time_ - Worst Case Linear Time Order Statistics - O(n)
    - _power_set_ - Power Set (Set of Subsets)
    - _searching_ -
      - _binary_search_ - Binary Search - O(log n)
      - _interpolation_search_ - Interpolation Search - O(n)
      - _linear_search_ - Linear Search - O(n)
      - _ternary_search_ - Ternary Search - O(log<sub>3</sub>n)
    - _sieve_of_eratosthenes_ - Sieve of Eratosthenes (Consecutive primes not exceeding n)
    - _sorting_ -
      - _binary_insertion_sort_ - Binary Insertion Sort - O(n<sup>2</sup>)
      - _bubble_sort_ - Bubble Sort - O(n<sup>2</sup>)
      - _bucket_sort_ - Bucket Sort - O(n<sup>2</sup>)
      - _counting_sort_ - Counting Sort - O(n + k)
      - _heap_sort_ - Heap Sort - O(nlog(n)
      - _insertion_sort_ - Insertion Sort - O(n<sup>2</sup>)
      - _merge_sort_ - Merge Sort - O(nlog(n))
      - _quick_sort_ - Quick Sort - Θ(nlog(n))
      - _radix_sort_ - Radix Sort - O(n+k)
      - _selection_sort_ - Selection Sort - (O(n<sup>2</sup>))
      - _shell_sort_ - Shell Sort - О(n)
    - _string_matching_ -
      - _boyer_moore_ - Boyer Moore Algorithm
      - _horspool_ - Boyer Moore Horspool Algorithm
      - _knuth_morris_pratt_ - Knuth Morris Pratt
      - _naive_pattern_matching_ - Naive Pattern Matching
      - _rabin_karp_ - Rabin Karp
    - _toh_ - Tower of Hanoi
2.  **graphs** -
    - _directed_unweighted_ - Directed Unweighted graph
    - _directed_weighted_ - Directed Weighted graph
    - _undirected_unweighted_ - Undirected Unweighted graph
    - _undirected_weighted_ - Undirected Weighted graph
3.  **heaps** -
    - _max_binary_heap_ - Max Binary Heap
    - _min_binary_heap_ - Min Binary Heap
4.  **linked_lists** -
    - _circular_doubly_ll_ - Circular Doubly Linked List
    - _circular_ll_ - Circular Linked List
    - _doubly_ll_ - Doubly Linked List
    - _pres_rev_single_ll_ - Preserve order during insertion on Single Linked List and Reversing Single Linked List
    - _single_ll_ - Single Linked List
5.  **queues** -
    - _cdqueue_ - Circular Double ended Queue
    - _cqueue_ - Circular Queue
    - _dqueue_ - Double ended Queue
    - _priority_queue_ - Priority Queue with the use of Min Heap
    - _simple_queue_ - Simple Queue
6.  **stack** - stack
7.  **trees** -
    - _avl_tree_using_ll_ - AVL Tree using linked list with BFS and DFS (Pre, In, Post) order traversals.
    - _bst_using_arr_ - Binary Search Tree using array with BFS and DFS (Pre, In, Post) order traversals.
    - _bst_using_ll_ - Binary Search Tree using linked list with BFS and DFS (Pre, In, Post) order traversals.
    - _simple_bt_using_arr_ - Simple Binary Tree using array with BFS and DFS (Pre, In, Post) order traversals.
    - _simple_bt_using_ll_ - Simple Binary Tree using linked list with BFS and DFS (Pre, In, Post) order traversals.

**Note**: The pointer &nbsp;"&nbsp;:point_left:&nbsp;"&nbsp; indicates incomplete implementation and is in todo list.

### Contribution

This repository is for learning how to implement data structures and algorithms, and since contributions of others won't really teach me how to implement it by myself, I won't be accepting any pull requests. However, feel free to fork this repo and modify the code to play around various data structures and algorithms. Moreover, while playing around the code, if you find anything unusual or wrong in the implemetation, I would highly appreciate if you create an issue on the same.

### License

This repository is released under the [MIT license](https://opensource.org/licenses/MIT). In short, this means you are free to use this software in any personal, open-source or commercial projects. Attribution is optional but appreciated.

```
HAPPY CODING 💻
HAPPY LEARNING 📚
```
