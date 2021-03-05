# labexercise5
## What does it do?
Our program asks for your favourite food and it suggests different types of food that you may also like based on your favourite food. Also, it suggest restaurants in your area based on your location and the restaurants rating.

## How to use it
### Installation
1. Go to the terminal
2. Change to the file you want the program to be in (cd)
3. Git clone our code into the file. 
https://github.com/apu-a/labexercise5.git

### Documentation and Examples
The labexercise5 program file needs to be in the same directory of your code, so it can be called upon using `from labexercise5 import *` 

After you called our program, you can use some of the functions avaiable in it. Such as:

suggestFood(): suggests different foods based on your favourite food. Returns a list of other food options.

```python
suggestedFood = suggestFood(favouriteFood)
```

ratingRestaurant(): provides the rating of restaurants near your location. Returns a list of restaurants, containing their name, location, foods, and rating.
```python
ratingRestaurant(location)
```

restaurantSearch(): searchs for restaurants in your area and returns a list of restaurants that serve the food you are searching. It calls upon the ratingRestaurant(), to acquire information about the restaurants.
```python
restaurantSearch(location, food)
```

commonFriend(): says that it likes the same food as you. Doesn't return anything. 
```python
commonFriend(food)
```

## How to contribute
[License](https://github.com/apu-a/labexercise5/blob/1e26f9906d62b5fb7cba83d61b6ce171d52c7ec3/LICENSE)

Code of Conduct: I used this code of conduct because I liked how they specified exactly how behavior should be conducted and the actions to take if someone violated any rules or acted inappropriately. This way it leaves little room for misbehavior and gives exact details of the standards everyone should be held to. 
[Code of Conduct](https://github.com/apu-a/labexercise5/blob/1e26f9906d62b5fb7cba83d61b6ce171d52c7ec3/CODE%20OF%20CONDUCT.md)


## Contributors
* Jack Bellamy 
* Helena Steffens 
* Apurvaa Anand
