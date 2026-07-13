# Module 4

*Help a friend debug a problem by only asking questions.*

**Target Skills: Constructive Inquiry, Verbal Precision, Accessible Communication**

## Task

The task was about helping a peer who was confused about why a Python shopping cart function kept "remembering" items from previous calls. The problem focused on debugging a function that used a mutable default argument (cart=[]).

## Process

The questions I asked were:
1. Walk me through what you think happens when this function is first defined.
2. How did you decide to use cart=[]?
3. What do you think is happening to the cart list after the first function call finishes?
4. What do you think needs to happen to the cart list so that each function call can start fresh?

## Deliverable

What happened after each question:
1. The individual explained how it creates an empty cart for the function to use. I noticed how this revealed that they think the list is created each time that it runs.  
2. They explained how they wanted the function to have a default empty cart at the start of each iteration.
3. They noticed how the list was being reused after every call. I noticed how this revealed to them how "apple" appeared before "banana" in the list.
4. They suggested creating a new list each time the function runs.

## Reflection

I feel that the question that moved the person furthest was question 3 because it helped to show them how what their expected workflow wasn't what the function was doing. This made them realize how the same list was being reused (which was what the bug was).

I felt the need to just hand over the answer most for question 2 because they were super close to the right idea. It was hard to not explain the correct conceptual idea but I told myself that continuing to ask them questions will eventually reveal the answer to them.

Next time, I would have them explain the bug in their own words at the end so they can confirm that they fully understood why it happened.
