# LISTEXERCISEUDEMY

//make a list
List<Integer> rollNumbers=new List<Integer>{111,333,222};
System.debug(rollNumbers);

//add items on a list
rollNumbers.add(9999);
rollNumbers.add(8888);
System.debug(rollNumbers);

//get item on index
System.debug(rollNumbers.get(1));
Integer num= rollNUmbers.get(1);
System.debug(num);
System.debug(rollNumbers.get(3));
Integer num1=rollNUmbers.get(2);
System.debug(num1);

//add item
rollNumbers.add(4,89898);
System.debug(rollNumbers);
rollNUmbers.get(2);
System.debug(rollNUmbers.get(2));

//get the list size
System.debug(rollNumbers.size());

//remove item from the list
rollNumbers.remove(2);
System.debug(rollNUmbers.remove(3));
System.debug(rollNUmbers);
System.debug(rollNUmbers.size());

//update item on index 2
rollNUmbers.set(1,56565);
System.debug(rollNUmbers);

//clear the list
rollNUmbers.clear();
System.debug(rollNumbers);
System.debug(rollNUmbers.size());
