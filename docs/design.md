##Design
Given a destination object that implements the cartography interface and another object of source data (either as a variable in the deztination object or as a sepwrate source) and a map the object Cartographer takes the map and the 2 objects and either copies the data to the destination object or points the destination object properties by refrence to the  source object. Maps may be array (numeric or key value), map object, or json. Modifier will be copy or by refrence. Each property can have an accessor modifier to the global accessor which tells how to access the property (one for the source and one for the destination)

This is useful for converting items to objects like flexible fields from laravel eloquent models. Even for bringing in input to an object.  Sources can be objects, arrays of objects, arrays.

Needs a cartography trait that provides the functions and variables to do the mapping.
