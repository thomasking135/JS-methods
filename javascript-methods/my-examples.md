// Write your two examples here

//We'd like you to research `two` methods and provide a code example and explanation 
//(for each one) of what that method does and could be used for. You can write your 
//examples in the `my-examples.js` file.

<h1>The some() Method</h1>

<p>This method tests to see if any array elements pass a test. It is a
    useful function for determining the existence or non existence of items in an array. It can be useful in helping to better understand the contents of an array.  
</p>

<p>
const pies = [4, 9, 16, 20];

pies.some(checkPies);
function checkPies(pies) {
  return pies > 18;
}
</p>

<p>The return on the console would be true as their are some pies greater than 18.</p>
<p>However if the function was changed to return pies > 20 the return on the console would be
    false as there are no volume of pies greater than the 20 which exist. 
</p>

<h1>The sort() Method</h1>

<p>The sort() function is commonly used. It allows one to sort elements of an array into a desired returned order. The default sort order is ascending. This works works numbers and alphabetical items. This method is good for clearly organising elements and easily finding elements in an array. It can also be combined with the reverse() method which shows items in a descending order. This can be useful when looking for higher or lower values. 

<p>
const cars = ["Mitsubishi", "Toyota", "Honda", "Nissan"];
fruits.sort();
</p>

<p>What would be returned is the vehicles in alphabetical order</p>