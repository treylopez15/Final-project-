air r onane Purhon comorerclass Movie
2 - class Movie:
def _init_(self, title, rating):
self.title = title
self.rating = rating
12
def get_average_rating(movies) :
total_ratings = sum(movie.rating for movie in movies)
return total_ratings / Len(movies)
def maino:
print("Welcome to the Simple Movie Dataset Analysis!")
# Samole movie data
movies = [
Movie("The Shawshank Redemption", 9.3), Movie("The Godfather", 9.2), Movie ("The Dark Knight", 9.0), Movie("Pulp Fiction", 8.9),
Movie("Inception", 8.8),
20
21
22
24
25
27
while True:
print("InMenu:")
print("1. Display Movie Statistics")
print(*2. Display Average Movie Rating")
print("3. Exit")
