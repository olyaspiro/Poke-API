For PokeAPI Assignment I have created HTML file including JS inside, and CSS for minor styling.
I started with creating an input box where users can enter the name or ID of a Pokémon, and added a button 'onclick' to trigger the search when clicked. 

After that I used a JS function to fetch and display Pokémon data asynchronously. 
The app uses async/await to fetch Pokémon data from the PokeAPI.
If the Pokémon name or ID is invalid, an error message like "Pokémon not found!" is shown in red.
If the input field is empty, a message prompting the user to enter a name or ID appears.
When the search is successful, the Pokémon's name, image, and types are displayed in a clean, readable format.

To dynamically update the DOM  based on the data received from the PokeAPI I:
- updated innerHTML of the pokemonDetails div with the fetched Pokémon's name, image, and types;
- displayed the image of the Pokémon using data.sprites.front_default;
- extracted the types using data.types.map();
- capitalized the name using data.name.charAt(0).toUpperCase() + data.name.slice(1).

  I used vanilla JavaScript, and tried to kepp my code simple and readable.
