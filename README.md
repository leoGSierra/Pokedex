# Pokedex

Hola!! este repositorio contiene una función de Python (`visualizar_pokemon`) que visualiza la información de un Pokémon almacenada en un archivo JSON. La función toma el nombre del Pokémon como argumento y muestra su nombre, imagen, peso, altura, movimientos, habilidades y tipos.

### Requisitos

- Python 3.6 o superior

### Uso

Para utilizar la función, sigue estos pasos:

1. Clona este repositorio en tu ordenador.
2. Guarda la información del Pokémon que quieras visualizar en un archivo JSON en la carpeta `pokedex`. El archivo JSON debe tener el siguiente formato:

###json
{
  "nombre": "nombre_del_pokemon",
  "imagen": "url_de_la_imagen_del_pokemon",
  "peso": "peso_del_pokemon_en_kg",
  "altura": "altura_del_pokemon_en_m",
  "movimientos": ["lista", "de", "movimientos"],
  "habilidades": ["lista", "de", "habilidades"],
  "tipos": ["lista", "de", "tipos"]
}

3. En un terminal, navega hasta el directorio donde hayas clonado el repositorio y ejecuta el siguiente comando:

       python visualizar_pokemon.py nombre_del_pokemon

Sustituye `nombre_del_pokemon` por el nombre del Pokémon cuyo archivo JSON quieres visualizar.

### Ejemplo


###Picachu
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/85aa64e1-e69d-4d07-9b82-cc3995ffbb5e)
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/80da101e-f18f-4ea8-a232-249a031a6dd2)
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/8b847260-67dd-4416-b6b6-fdcab3662087)

Por ejemplo, para visualizar la información del Pokémon Pikachu, puedes ejecutar el siguiente comando:

      python visualizar_pokemon.py pikachu

Esto mostrará la siguiente información:

**Nombre:** Pikachu
**Imagen:** https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png
**Peso:** 6.0 kg
**Altura:** 0.4 m
**Movimientos:**
 - Impactrueno
 - Cola de Hierro
 - Rayo
 - Voltiocambio
**Habilidades:**
 - Pararrayos
 - Electricidad Estática
**Tipos:**
 - Eléctrico

   
###Charmander
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/330847e9-5c32-4cf3-864b-73195371247b)
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/c4b42245-a0b4-4cc5-b6e0-8292181c4d21)
![image](https://github.com/leoGSierra/Pokedex/assets/159668138/8ff0c2c4-5851-4433-ba4a-164a26f38318)

###Refelxiones del bootcamp

Este curso me ah enseñado a como usar una API publica, como extraer datos y guardarlos, el proceso fue un poco divertido ya que se uso una API de pokemones, la verdad fue algo muy interesante, agradesco a mi profesora por sus enseñansas, espero aprender mucho mas. :)

