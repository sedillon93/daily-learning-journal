# Making tables

When looping through an array within an array, remember to change your indexing variable for the inner loop; they can't both use i (use j instead for the second loop). Also when accessing the value you want in the inner loop remember that you are accessing an element at a specific index of an array <em>within an element at a specific index of another array</em>.
