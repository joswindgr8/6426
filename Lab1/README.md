# ISCG 6426 Lab 1 Semester 1 2020.
## by Kris Pritchard

ISCG6426 Lab1 Semester 1 2020. Code by Kris Pritchard / @krisrp
Implement the following:

* ex1: A recursion base case.
* ex2: Stack class and Stack Exceptions
* ex3: Queue class and Queue Exceptions
* ex4: Tuple class and Tuple Exceptions
* ex5: Dictionary class and Dictionary Exceptions (Technically just the interface for now, but illustrative)
* ex6: Set class and Set Exceptions
* ex7: PriorityQueue class and import the Queue Exceptions from exercise 3.


ex0_list_example has been implemented to show how to do it.

## NOTE: Each method only requires 1-7 lines of code. If you have more you're doing it wrong.


Lab1: Implement the data structures to make all the tests pass.

### Step 1 - Download the code

```shell
git clone https://github.com/kris-classes/6426
```

### Step 2 - Install the required libraries


```shell
pip install -r requirements.txt
```

### Step 3 - Running the tests.


NOTE: **CONTACT ME IF THIS DOES NOT WORK FOR YOU OR IF ANY TESTS DON'T PASS**
```shell
# Example with Lists
pytest -xv ex0_list_example_tests.py
# Recursion
python ex1_recursion_tests.py  # NOTE: This example just uses python, not pytest.
# Stack
pytest -xv ex2_stack_tests.py
# Queue
pytest -xv ex3_queue_tests.py
# Tuple
pytest -xv ex4_tuple_tests.py
# Dictionary
pytest -xv ex5_dictionary_tests.py
# Set
pytest -xv ex6_set_tests.py
# PriorityQueue
pytest -xv ex7_priorityqueue_tests.py
```

### Step 4 - Make the data structures work.

Fix each of the tests one by one.

The files you need to fix are:
* ex1_recursion.py
* ex2_stack.py
* ex3_queue.py
* ex4_tuple.py
* ex5_dictionary.py
* ex6_set.py
* ex7_priorityqueue.py

Create copies of them and upload them to a private DSA_Labs repository you
create. Add me (@krisrp) as a collaborator to the repository.

``` shell
pytest -xv ex2_stack_tests.py  # Runs the Stack tests.
```

Here you will get 
```python
AssertionError: Expect 'Stack __str__(): FIX ME' to equal '<Stack __str__: []>'
```

Fix the Stack.__str__ method in ex2_stack.py so that the test passes.
Commit your fixed code to GitHub.

Now fix the __repr__ method.
Commit your fixed code to GitHub.

And continue.
