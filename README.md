# Design-Pattern-Adapter

- The goal is to convert the String input into an output like an ArrayList<Character> using adapter design pattern.<br />

- The roles in the adapter design pattern are an adapter, an adaptee, a target interface and a client. <br />
o Class CollectionCharacter is the adapter will convert the String input into a Vector<Character>. <br />
o The String input is the client. <br />  
o The ArrayList class is the adaptee. <br /> 
o The target interface, Collection<Character>. <br /> 
o Both the adapter class and the ArrayList class implements t
  
Note that in this project, the class CollectionCharacter extends class Vector and implements interface Collection. <br />
The class Vector has already implemented the methods in the interface Collection, so it is not neccessary to override the method in the class CollectionCharacter.  

This also means that the methods from the Vector can be used. For example, the iteration in the main class uses the interation method in the Vector class. 


If the class CollectionCharater does not extend class Vector, the methods in the interfaces will be implemented in the CollectionCharacter. The implementation will possibly start from: <br />
1. converting the String input into char array, <br />
2. converting the String input into ArrayList or  <br />
3. using String type  <br />
 

  