# https://git-profile-viewer-kappa.vercel.app/

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# GitHub User Profile Viewer

The **GitHub User Profile Viewer** is a React-based web application that allows users to search for and view GitHub user profiles based on their username. This application fetches and displays user profiles from GitHub's API and provides a user-friendly interface for searching.

## Features

- Input field for entering a GitHub username.
- Fetches GitHub user profiles based on the provided username.
- Displays user avatars, login names, user IDs, and links to the user's GitHub profile.
- Provides error handling for invalid usernames or network issues.
- Implements debouncing to prevent unnecessary API requests.

## Technologies Used

- React: The application is built using the React JavaScript library.
- CSS: Styling is applied using CSS.
- GitHub API: The application fetches user profiles from GitHub's API.

## Components

### GitViewer

- The main component for the GitHub User Profile Viewer.
- Manages user input, fetches data from the GitHub API, and displays user profiles.
- Utilizes debouncing to prevent excessive API requests.

### ShowGitUserProfile

- A child component responsible for rendering individual user profiles.
- Receives user profile data as props and displays user details.

## How to Use

1. Clone the Repository:

   ```bash
   git clone https://github.com/your-username/github-user-profile-viewer.git
   cd github-user-profile-viewer
   ```

2. Install Dependencies:

   ```bash
   npm install
   ```

3. Start the Development Server:

   ```bash
   npm start
   ```

4. Open the Application:

   Open your web browser and navigate to `http://localhost:3000`. You will see the GitHub User Profile Viewer.

5. Search for GitHub Profiles:

   - Enter a GitHub username in the input field and press Enter or click the "Search" button.
   - The user profiles matching the provided username will be displayed with user avatars, names, IDs, and links to their GitHub profiles.
   - If no data is found or there is an error, an error message will be displayed.

## Customization

You can further customize the application by modifying the CSS styles in the CSS files, changing the appearance of user profiles, or adding additional features.

Feel free to replace `your-username` in the clone command with your actual GitHub username. This README provides an overview of your GitHub User Profile Viewer application and instructions for using and customizing it.
