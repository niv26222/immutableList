# immutable List



ImmutableList, as suggested by the name, is a type of List which is immutable. It means that the content of the List are fixed or constant after declaration, that is, they are read-only.
If any attempt made to add, delete and update elements in the List, UnsupportedOperationException is thrown.
An ImmutableList does not allow null element either.
If any attempt made to create an ImmutableList with null element, NullPointerException is thrown. If any attempt is made to add null element in List, UnsupportedOperationException is thrown.


From existing List using copyOf() function of Guava
