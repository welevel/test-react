# test-react

1. Create a fresh react project:
    ```bash
    # bootstrap project
    npm install -g yarn react-create-app
    react-create-app test-react
    cd test-react

    # initialize git repository and store the initial state as commit
    git init
    git add .
    git commit -m 'Initial commit'

    # start project in development mode
    yarn start
    ```
2. Edit the project to render a list of posts. The data for the posts is available at a public test REST API at https://jsonplaceholder.typicode.com/. For example: 
    * List post: `GET https://jsonplaceholder.typicode.com/posts`
    * Get post details: `GET https://jsonplaceholder.typicode.com/posts/1`
3. For every post show a button to unfold a list of comments for the post:
    * Get post comments: `GET https://jsonplaceholder.typicode.com/posts/1/comments`
4. Commit your changes. Create a fresh GitHub repository, push your solution and give us the link to your repository.