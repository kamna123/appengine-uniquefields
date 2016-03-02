#UniqueFields Class help you add unique field constraints to App Engine Entities



&lt;A href="http://e.xtrahelp.com/programming/appengine/unique-field-constraints-for-entity-attributes"&gt;

Unique Fields class - HOW TO GUIDE

Unknown end tag for &lt;/a&gt;



# Introduction #

To add unique field constraints in our Java applications, we have created a UniqueFields class that takes cares of adding unique field constraints to our entity attributes.

Basically, the UniqueFields class stores these values in a separate Unique Field Store that allows us to check for the availability of unique values and assign them to individual entities.

Advantages of this approach:

- you can have multiple unique field constraints on your entities

- no need to use ancestor queries

- no need for parent entities or entity groups

- stores the unique field value in the creating entity so that you can still filter, search and index based on the unique field values


# Details #
see the guide at http://e.xtrahelp.com/programming/appengine/unique-field-constraints-for-entity-attributes for details and instructions on how to use this class in your project