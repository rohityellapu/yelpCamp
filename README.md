# YelpCamp
A Social Media platfrom for sharing best local campgrounds 



## Working Tree
```cmd
│   .gitignore
│   app.js
│   middleware.js
│   package.json
│   README.md
│   schemas.js
│
├───cloudinary
│       index.js
│       
├───controllers
│       campgrounds.js
│       reviews.js
│       users.js
│
├───models
│       campground.js
│       review.js
│       user.js
│
├───public
│   ├───javascripts
│   │       clusterMap.js
│   │       showPageMap.js
│   │       validateForms.js
│   │
│   └───stylesheets
│           app.css
│           home.css
│           stars.css
│
├───routes
│       campgrounds.js
│       reviews.js
│       users.js
│       
├───utils
│       catchAsync.js
│       ExpressError.js
│
└───views
    │   error.ejs
    │   home.ejs
    │
    ├───campgrounds
    │       edit.ejs
    │       index.ejs
    │       new.ejs
    │       show.ejs
    │
    ├───layouts
    │       boilerplate.ejs
    │
    ├───partials
    │       flash.ejs
    │       footer.ejs
    │       navbar.ejs
    │
    └───users
            login.ejs
            register.ejs
```
