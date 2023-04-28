# Text-Editor
- This is a text editor built with webpack bundling. It allows the user to download the program so that it is available offline via service worker.

## Details
- The file structure of the app is a client / server structure. It allows for the separation of the front end and backend development environments. Using the Webpack module i was able to bundle my assets together in an organised way. Keeping the functional side of things separate from assets and the front end from the back end etc. Bundling assets is a great way to boost performance of apps.
## what i learned

- I learned a lot about the importance of file structure and configuration files for webpack. The config file has a bit of a rigid structure in terms of what plugins you're using. The manifest was an interesting way to handle modules efficiently at runtime due to how it accesses thim via id. I learned that service workers are a good way to preserve resources, and intercepts requests to serve cached resources.

## link to application
- https://kipptexteditor.herokuapp.com/
