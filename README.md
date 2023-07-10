# Reddit Simulator

![Reddit Simulator Banner](./banner.png)

Reddit Simulator is a project that simulates a Reddit server by fetching posts and comments from the Reddit API. It provides a user interface to browse and interact with the fetched data, allowing users to view posts, toggle comments, and perform various actions.

## Features

- Fetches posts from the Reddit API based on the selected subreddit.
- Displays a loading animation while fetching data.
- Allows users to toggle comments for each post.
- Fetches comments for a post when the comments are toggled.
- Provides error handling for failed API requests.
- Allows users to retry fetching posts in case of an error.
- Supports filtering posts based on search terms.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Redux: A predictable state container for JavaScript apps.
- react-redux: Official React bindings for Redux.
- react-animated-list: A library for animating lists in React.
- Reddit API: The API provided by Reddit to fetch posts and comments.

## Installation

1. Clone the repository: `git clone https://github.com/rafaelfalleiros/reddit-simulator-react-redux.git`
2. Navigate to the project directory: `cd reddit-simulator-react-redux`
3. Install the dependencies: `npm install`
4. Start the development server: `npm start`
5. Open the application in your browser at `http://localhost:3000`

## Usage

1. Enter a subreddit name in the search bar to fetch posts from that subreddit.
2. Click on the "Toggle Comments" button to view the comments for a post.
3. If an error occurs while fetching posts, click on the "Try Again" button to retry.
4. Explore the different posts and comments within the application.
5. Have fun simulating your own Reddit server!

## Bugs and Issues

Some bugs were detected throughout this project's development:
1. The "Toggle Comments" button does not work properly when the comments are already toggled.
2. The "Try Again" button does not work properly when an error occurs while fetching posts.
3. The Search bar does not work properly the user tries to search for a subreddit.

## Contributing

Contributions are welcome! If you find any other bugs or have suggestions for improvement, please open an issue or submit a pull request. Make sure to follow the project's code of conduct.

## License

This project is licensed under the [MIT License](./LICENSE).
