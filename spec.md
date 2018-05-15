# Koocot - Back-end for the app

## Things users can do

Phase 1:
* Recipes can be added to the app with minimal work from user
* It's possible to receive a list of recipes, based on a certain criteria


Phase 2 - Additions:
* User should be able to create an account (email password)
* User should be able to change password
* User should be able to change name


## First Iteration

First iteration will include just the methods to create recipes and get the list of them, the app is agnostic of any users at that point, only has a list of records for the recipes.


## API Endpoints

### /add

Gets a POST request (?) with the Recipe object, and should know what user it is associated with. Not sure if we should send the Recipe object, or just some information needed to create it and then the app would return the Recipe object.

 The app should also let the user know if the request was a success (potentially return back the Recipe object), or 



### /recipes 

It should receive a POST (?) request with the following info (After that it should send back a list of recipes):

RecipeList request:
{
  
}






## Structs (?)

// Intentionally keeping this simple, since we want to make it very easy for users to add recipes.
Recipe {
  URL string
   
  Rating int (optional, 0-10)
  
}

User {
  email string
  name string
  password string (some sort of hash?)
}

FoodCategories to use

Breakfast, Soup, Salad, Dessert, Main, 





