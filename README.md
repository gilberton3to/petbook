# Pet Name Generator & Collection Manager

<img width="674" alt="Screenshot 2024-03-26 at 10 50 13" src="https://github.com/gilberton3to/petbook/assets/72652382/54a63351-7eb8-4738-a089-9e77ea478bed">


This is a command line program (CLI) developed to help you manage your collection of pets, choose the name of your pets by generating
random names from the category of your choosing. You can add, delete and view all your pets.

## Features

- **Name Generator**: Generate new creative and unique names for your pets.

- **Pet Registration**: Register your pets in a collection to maintain organized control.

- **Easy to Use**: Simple and intuitive interface for a friendly user experience.

## Language

Be sure to find out the language:

- Swift

## How To Use

**SUBCOMMANDS:**

-generate

-edit

-view


**OVERVIEW: Generate**

**USAGE:** 

petbook generate <animal> [OPTIONS]


**ARGUMENTS:**

<animal> generates the name of an animal, possibilities: 'cat', 'dog', 'bird', 'fish' or 'others'.


**FLAGS:**

-m, --mythological Generate a mythological name.

-p, —-person Generate a human name.

-c, —-cute Generate a cute name.


**OVERVIEW: Edit**

**USAGE:** 

petbook edit <pet-name> [OPTIONS]


**ARGUMENTS:**

<pet-name> the name of the pet you want to add or delete in your collection, eg. 'edit <pet-name> -i'.


**OPTIONS:**

-i, --insert Adds a new pet to your collection.

-d, --delete Deletes a pet of your choosing from your collection.


**OVERVIEW: View**

**USAGE:**

petbook view <collection> [OPTIONS]


**ARGUMENTS:**

<collection> shows your collection of pets or the collection of the names the app can give you. possibilities: 'pets' or 'animal-names'.

**FLAG:**

-d, --delete Delete all pets from a collection.
