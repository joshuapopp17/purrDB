# purrDB 🐾
Thank you for using purrDB
Yeah I like cats.😻

This is a 100% client side DB using localstorage in the web browser.
I got annoyed using all these third party API's just to make a simple web app.
For that reason I made my own local storage interface to make it easy.
It's a work in progress but I am happy with it so far. 

# 📄 INSTRUCTIONS AND USAGE 📄:
## CREATE A NEW COLLECTION:
createCollection("collection")

## DELETE A COLLECTION:
deleteCollection("collection")

## GET A COLLECTION (all rows or with conditon):
getCollection("collect", ?condition = {"eq or neq": JSON OBJECT})
#### EX: const data = getCollection("users", {"eq": {name: "josh"}})

## GET A SINGLE ROW:
getRow("collection", id)

## INSERT A SINGLE ROW:
insertRow("collection", JSON OBJECT)

## UPDATE A SINGLE ROW:
updateRow("collection", id, JSON OBJECT)

## DELETE A SINGLE ROW:
deleteRow("collection", id)
