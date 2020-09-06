Rock, Paper, Scissors
---
In this project I made a simple rock, paper, scissors game using Javascript DOM manipulation and conditional statements.

Issues encountered:

replay.addEventListener('click', location.reload()); I was having problems getting this code to work as intended. The reason was that I was calling the function instead of passing it as a parameter for callback. This was fixed by adding an anonymous function that calls location.reload() in the second argument. replay.addEventListener('click', () => location.reload());

https://stsui1129.github.io/rock-paper-scissors/

Next update: Add CSS to the page.