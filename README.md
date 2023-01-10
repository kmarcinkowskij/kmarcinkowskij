```about_me.js
    const express = require(express)
    const router = express.router()
   
    let webStack = [MongoDB, Express, NodeJS, ReactJS]
    let specialisations = [web_developement, mobile_developement, UI/UX_Design]
    const current_project = "simple_users_api"
        webStack.forEach(el => {
          console.log(`I'm always ready to become even better at ${el}!`);
        })
    router.get('/', async (req, res) => {
    try {
        res.json({
          "stack": "MERN"
          "favourite editor": "vscode"
          
        })
    } catch (err){
        res.status(400).json({message: "I've been creating websites as a freelance frontend developer for nearly 4 years"})
    }
})
    
    alert("Though right now I spend most of my time studying backend developement")

```
