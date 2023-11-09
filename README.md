# frontend-prep

just testing stuff for interviews. my answers to these were either in plain js or created from a [create react app](https://create-react-app.dev/)

## links

- [breaking bad one](https://breakingbad.rickcel.com/)
- [collection of everything else](https://prep.rickcel.com/)

## testing prompts

### breaking bad name generator

Create a simple ui that takes a first name and last name and outputs a title similar to the breaking bad title:

![Breaking Bad title, Br and Ba are stylized in the way you see it in a periodic table](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Breaking_Bad_logo.svg/440px-Breaking_Bad_logo.svg.png)

Requirements:

- two input fields for first and last name
- a submit button
- when submit button is clicked an output is generated
- for each name find the first occurance of a periodic element abbreviation. In the output put that part of the name in a green box with white text, the rest of the name is green. See the image above for an example.

the elements are as follows:

```
const ELEMENTS = [
        "Ac",
        "Al",
        "Am",
        "Sb",
        "Ar",
        "As",
        "At",
        "Ba",
        "Bk",
        "Be",
        "Bi",
        "Bh",
        "B",
        "Br",
        "Cd",
        "Ca",
        "Cf",
        "C",
        "Ce",
        "Cs",
        "Cl",
        "Cr",
        "Co",
        "Cn",
        "Cu",
        "Cm",
        "Ds",
        "Db",
        "Dy",
        "Es",
        "Er",
        "Eu",
        "Fm",
        "Fl",
        "F",
        "Fr",
        "Gd",
        "Ga",
        "Ge",
        "Au",
        "Hf",
        "Hs",
        "He",
        "Ho",
        "H",
        "In",
        "I",
        "Ir",
        "Fe",
        "Kr",
        "La",
        "Lr",
        "Pb",
        "Li",
        "Lv",
        "Lu",
        "Mg",
        "Mn",
        "Mt",
        "Md",
        "Hg",
        "Mo",
        "Mc",
        "Nd",
        "Ne",
        "Np",
        "Ni",
        "Nh",
        "Nb",
        "N",
        "No",
        "Og",
        "Os",
        "O",
        "Pd",
        "P",
        "Pt",
        "Pu",
        "Po",
        "K",
        "Pr",
        "Pm",
        "Pa",
        "Ra",
        "Rn",
        "Re",
        "Rh",
        "Rg",
        "Rb",
        "Ru",
        "Rf",
        "Sm",
        "Sc",
        "Sg",
        "Se",
        "Si",
        "Ag",
        "Na",
        "Sr",
        "S",
        "Ta",
        "Tc",
        "Te",
        "Ts",
        "Tb",
        "Tl",
        "Th",
        "Tm",
        "Sn",
        "Ti",
        "W",
        "U",
        "V",
        "Xe",
        "Yb",
        "Y",
        "Zn",
        "Zr",
      ]
```

example [here](https://breakingbad.rickcel.com/)

### tic tac toe

create a tic tac toe game. supports two players taking turns. outputs if there's a winner or tie.

- create ui for a board
- clicking on a square in the board enters the x/o
- display who's turn it is
- check for a winner/tie after each turn
- display when a winner/tie is found (prevent adding more x/o in this state)
- a button to restart game

### nav

implement a simple nav. should have one nav that has a sub nav that shows on hover. on resize to a mobile size change to a hamburger menu.

requirements:

- responsive navigation bar
- at least one nav has a sub menu that shows on hover
- hamburger menu shown on mobile screen, nav is full screen on hamburger click

### to do list

create a simple to do list.

requirements

- list starts empty
- input field at the bottom of list, submitting that adds to list
- each list item can be checked off or deleted
- bonus: remember to do list on refresh (using local storage or something)
