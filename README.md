# GitHub Profile Search

This project is a simple web application that allows users to search for GitHub profiles by username. It fetches user data using the GitHub API and displays information such as the user's name, bio, number of followers, following, public repositories, and a list of their recent repositories.

---

## Live Demo

🚀 **[Try it Live Here](https://imtahirnaseer.github.io/github-Profile-Search/)**

---

## Features

- **Search GitHub Users**: Enter a GitHub username to fetch and display profile details.
- **User Information**: Displays user name, bio, followers, following, and number of public repositories.
- **Repositories**: Lists the five most recently created public repositories with clickable links.
- **Error Handling**: Displays an error message if the username is not found or if there is a problem fetching data.

---

## Project Structure

### Files

1. **index.html**: 
   Contains the structure of the application, including a search input field and a container (`main`) to display user data.

2. **style.css**: 
   Provides styling for the application, including a responsive design, hover effects, and a visually appealing layout.

3. **script.js**: 
   Contains the JavaScript logic for interacting with the GitHub API, handling user input, and dynamically rendering the user profile and repositories.

---

## How It Works

### 1. HTML Structure
The `index.html` file defines:
- An input field for searching a GitHub username.
- A `<main>` element to display the fetched profile information.

```html
<form class="user-form" id="form">
  <input type="text" placeholder="Search a GitHub User" id="search" />
</form>
<main id="main"></main>
