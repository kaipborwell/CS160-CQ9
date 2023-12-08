# CS160-CQ9
The run time of Java's collection.sort is O(nlogn) where n is the size of the input array. In the case of the mini-max sum, it sorts the input array once which takes O(nlogn) time and the work done inside the for loop is constant time done n times and hence the overall time complexity is O(nlogn).
The space complexity of mini-max sum is determined by the space taken during the sorting process as the rest of the oeprations take constant space. The sorting operation uses O(logn) space, therefore the space complexity is O(logn). 

The time complexity of weighted uniform strings is O(n+q) because the while loop in the worst case iterates through all the characters of string s which is n and the for loop iterates through the entire list<integer> queries which has size q. In each case the work doen inside of the loop is constant work and hence the time complexity is the run time of each of the loops combined for O(n+q). 
The hashset is used to store the weight of the substrings which in the worst case, each of the substring has different weights which will store n values corresponding to the size of the input array. Hence the space complexity of weighted uniform strings is O(n). 
