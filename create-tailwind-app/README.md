# create-tailwind-app
A bash script to create a new react app and install tailwind css

## usage
`create-tailwind-app my-app-name`

1. runs create-react-app my-app-name
2. follows the Tailwind CSS to install tailwind in a react app
3. individually prompts to optionally install:
    - Headless UI
    - Axios
    - React-Icons
    - React-Router

### flags
`-a` - skips all prompts and installs all above mentioned pacakges

`create-tailwind-app my-app-name -a`