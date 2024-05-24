.body{
    background-color: #bcbce2;
    display: flex;
    flex-direction: column;
    padding: 40px;
    margin: 10px;
}
.titulo{
    font-family: "Libre Baskerville", serif;
    font-weight: 400;
    font-style: italic;
    background-color: #807faf;
    margin: 40px;
    padding: 15px;
    color: black;
    text-align: center;
    border-radius: 20px;
    
}
.espaco{
    font-family: "Libre Baskerville", serif;
    font-weight: 400;
    background-color: #6a69a7;
    padding: 15px;
    text-align: center;
    border-radius: 20px;
}
.corpoParag{
    margin: 40px;
    padding: 15px;
    border-radius: 20px;
    background-color: #807faf;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
}

nav ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
    background-color: #6a69a7;
    padding: 10px;
}

nav ul li {
    color: #000000;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.gallery img {
    flex: 1 1 calc(33.333% - 10px);
    max-width: 100%;
    height: auto;
    box-sizing: border-box;
}

.container {
    display: flex;
    padding: 10px;
}

header {
    grid-area: header;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
}

aside {
    grid-area: aside;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
}

main {
    grid-area: main;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
}

footer {
    grid-area: footer;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
}


nav a {
    color: #000;
    text-decoration: none;
    transition: color 0.3s;
}

nav a:hover {
    color: #6a69a7;
}

button {
    padding: 10px 20px;
    background-color: #6a69a7;
    color: #fff;
    border: none;
    cursor: pointer;
    transition: transform 0.3s, background-color 0.3s;
}

button:active {
    transform: scale(1.2);
    background-color: #;
}

button:hover {
    background-color: #6a69a7;
}

ul li:nth-child(odd) {
    background-color: #807faf;
}

ul li:nth-child(even) {
    background-color: #6a69a7;
}

h1::before {
    content: '⚡';
    margin-right: 10px;
}

h1::after {
    content: '⚡';
    margin-left: 10px;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;

form {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
}

textarea {
    height: 100px;
}

button {
    background-color: #6a69a7;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
    font-size: 16px;
}

button:hover {
    background-color: #815f91;
}

body {
    font-family: Arial, sans-serif;
}

.container {
    display: grid;
    grid-template-areas: 
        "header header"
        "aside main"
        "footer footer";
    grid-gap: 10px;
    padding: 10px;
}

header {
    grid-area: header;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
    text-align: center;
}

aside {
    grid-area: aside;
    background-color: #807faf;
    color: #fff;
    padding: 20px;
}

main {
    grid-area: main;
    background-color: #807faf;
    color: #fff;
    padding: 20px;
}

footer {
    grid-area: footer;
    background-color: #6a69a7;
    color: #fff;
    padding: 20px;
    text-align: center;
}








    padding: 10px;
}

nav ul li {
    color: white;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.gallery img {
    flex: 1 1 calc(33.333% - 10px);
    max-width: 100%;
    height: auto;
    box-sizing: border-box;
}

.container {
    display: grid;
    grid-template-areas: 
        "header header"
        "aside main"
        "footer footer";
    grid-gap: 10px;
    padding: 10px;
}

header {
    grid-area: header;
    background-color: #ff5733;
    color: #fff;
    padding: 20px;
}

aside {
    grid-area: aside;
    background-color: #c70039;
    color: #fff;
    padding: 20px;
}

main {
    grid-area: main;
    background-color: #900c3f;
    color: #fff;
    padding: 20px;
}

footer {
    grid-area: footer;
    background-color: #581845;
    color: #fff;
    padding: 20px;
}

@media (max-width: 768px) {
    .container {
        grid-template-areas: 
            "header"
            "main"
            "aside"
            "footer";
    }
}

nav a {
    color: #000;
    text-decoration: none;
    transition: color 0.3s;
}

nav a:hover {
    color: #ff5733;
}

button {
    padding: 10px 20px;
    background-color: #ff5733;
    color: #fff;
    border: none;
    cursor: pointer;
    transition: transform 0.3s, background-color 0.3s;
}

button:active {
    transform: scale(1.2);
    background-color: #c70039;
}

button:hover {
    background-color: #ff5733;
}

ul li:nth-child(odd) {
    background-color: #f0f0f0;
}

ul li:nth-child(even) {
    background-color: #c0c0c0;
}

h1::before {
    content: '⚡';
    margin-right: 10px;
}

h1::after {
    content: '⚡';
    margin-left: 10px;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

form {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
}

textarea {
    height: 100px;
}

button {
    background-color: #ff5733;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
    font-size: 16px;
}

button:hover {
    background-color: #c70039;
}

body {
    font-family: Arial, sans-serif;
}

.container {
    display: grid;
    grid-template-areas: 
        "header header"
        "aside main"
        "footer footer";
    grid-gap: 10px;
    padding: 10px;
}

header {
    grid-area: header;
    background-color: #ff5733;
    color: #fff;
    padding: 20px;
    text-align: center;
}

aside {
    grid-area: aside;
    background-color: #c70039;
    color: #fff;
    padding: 20px;
}

main {
    grid-area: main;
    background-color: #900c3f;
    color: #fff;
    padding: 20px;
}

footer {
    grid-area: footer;
    background-color: #581845;
    color: #fff;
    padding: 20px;
    text-align: center;
}

/* Media Queries for Responsiveness */
@media (max-width: 768px) {
    .container {
        grid-template-areas: 
            "header"
            "main"
            "aside"
            "footer";
    }
}

@media (max-width: 480px) {
    body {
        font-size: 14px;
    }

    header, aside, main, footer {
        padding: 10px;
    }
}

