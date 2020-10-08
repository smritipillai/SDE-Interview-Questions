
# Amazon Interview Questions
* [Coding Round Questions](#coding)
* [Technical Interview Questions](#tech)
   * [Data Structures and Algorithms](#dsalg)
   * [DBMS](#dbms)
   * [Operating System](#os)
   * [System Design](#design)
____
<b name="coding">Coding round questions</b><br/>
- Given an array of distinct elements and a number x, find if there is a pair with product equal to x.
- Given a string ‘str’ of digits and an integer ‘n’, build the lowest possible number by removing ‘n’ digits from the string and not changing the order of input digits.
- Given a number, find its corresponding Roman numeral.
- Given a linked list, write a function to reverse every k nodes (where k is an input to the function).
- Given phone digits, print all possible words that can be formed from them.
- You are given an array of integers. Return an array of the same size where the element at each index is the product of all the elements in the original array except for the element at that index.
For example, an input of [1, 2, 3, 4, 5] should return [120, 60, 40, 30, 24].
You cannot use division in this problem.
- Given a linked list and two integers M and N.
  Traverse the linked list such that you retain M nodes then delete next N nodes, continue the same till the end of the linked list.
For example, an input of M = 2, N = 2 Linked List: 1->2->3->4->5->6->7->8 should return Linked List: 1->2->5->6

- Given an array consisting many inner arrays, flatten the array into one:
  example: input: [[6,4,7,[9,5,4,[2,4,8]]],[2,2,7],[9,0,7,[9,3,1,8,5]]]
           output: [6,4,7,9,5,4,2,4,8,2,2,7,9,0,7,9,3,1,8,5]
 
- Given two sorted linked lists, merge them so that the resulting linked list is also sorted.

- Check if a given tree is a subtree of another binary tree.  
</br>

----
<b name="tech">Technical Interview Questions</b>
<br/>
<i><u name="dsalg">Data Structures and Algorithms</u></i>

<br/>
<i><u name="dbms">DBMS</u></i>

<br/>
<i><u name="os">Operating System</u></i>

<br/>
<i><u name="design">System Design</u></i>

 - Design a system that controls traffic lights with below assumptions:

   1. A group of traffic lights has two components: main lights and pedestrian lights.
   1. Main traffic lights have three colors: red, yellow and green.
   1. Pedestrian lights have two colors: red and green.
   1. Pedestrian lights' colors are reversed from main lights:
     - Main: red/yellow - pedestrian's: green
     - Main: green - pedestrian: red
   1. There is a button for pedestrian lights if the button is pushed in advance, pedestrian's lights change colors according to the main ones if the button isn't pushed, pedestrian's lights remain red.
   1. A typical junction has 4 groups of lights.
   1. Additional question: design the system in a way that allows cars which start from one junction after a red light don't have to stop at the next one.

  - Design a card game by considering the following assumptions:

    1. There should be more than one method of cards distribution such as even distribution, uneven distribution, etc.
    1. There are multiple situations which could be considered as a winning situation:
      - One who finishes all his cards early.
      - One who earns the maximum points at the last.

  - Design a task management system like Trello with the following assumptions:
    1. User can move tasks from one lane to the other and move it back.
    2. This should have a state diagram with many end states.
<br/>
<br/>
<i><u name="misc">Miscellaneous</u></i>
