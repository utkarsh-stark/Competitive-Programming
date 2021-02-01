## **[Java 1D Array (Part 2)](https://www.hackerrank.com/challenges/java-1d-array)** 
Let's play a game on an array! You're standing at index of an -element array named . From some index (where ), you can perform one of the following moves:<br><ul><li>Move Backward: If cell exists and contains a , you can walk back to cell .</li><li>Move Forward:
If cell contains a zero, you can walk to cell .
If cell contains a zero, you can jump to cell .
If you're standing in cell or the value of , you can walk or jump off the end of the array and win the game.</li><li>If cell contains a zero, you can walk to cell .</li><li>If cell contains a zero, you can jump to cell .</li><li>If you're standing in cell or the value of , you can walk or jump off the end of the array and win the game.</li></ul><br><ul><li>If cell contains a zero, you can walk to cell .</li><li>If cell contains a zero, you can jump to cell .</li><li>If you're standing in cell or the value of , you can walk or jump off the end of the array and win the game.</li></ul><br>In other words, you can move from index to index , , or as long as the destination index is a cell containing a . If the destination index is greater than , you win the game.<br>Given and , complete the function in the editor below so that it returns true if you can win the game (or false if you cannot).<br><br>**Sample Input 0**<br><br>**Sample Output 0**<br><br>**Explanation 0**<br><br>