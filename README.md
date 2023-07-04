# Install

`npm install`

---

# Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

---

# Run

`npm start`

#adding more features to this app

1. Add a delete button and delete ability to each comment which is only visible to the user who submitted the comment.

- The user who created the comment's ID
- a button
- a conditional statement in the view that compares the logged in user with the comment user ID
- a controller with a delete method
- a route to the controller
- DB storage of the user ID who created the comment -DONE

2. Add the username associated with each comment to the comment text.

- find the username based on the user ID attached to the comment.


