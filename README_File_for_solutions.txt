Part 1:


- Question:-
 The service fails to start - npm run start:dev - Use the messages to fix the code, so that the service runs successfully

- Solution:-
The function was declared to return a promise but it wasn't retruning a value. A return value is must. So I just add a return in the function, and the run time error get resolved.


Part 2:


- Question:-
 A test is failing - npm run test - implement the code necessary to pass the test

- Solution:-
There is a problem in delete function. The chatmessage is coming as empty and that's why at the end, where it meant to be false or true it receives empty object which fails the test.


