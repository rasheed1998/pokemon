API endpoint: https://pokeapi.co/api/v2/pokemon?limit=100
Display the data from the above API using pagination with 10 items per page. Use the “name” key from the API data to display.
Clicking on each name, another API call should be made using the “url” key from the existing API data to display the details of single pokemon.
Details of a single pokemon should be displayed in a separate route and the view should be in this format:
Left: Image of the pokemon (Construct the image URL using “https://pokeres.bastionbot.org/images/pokemon/${pokemonID}.png”)
Right: “name”, below display the names of all the “types”
