## Diagram
![image](https://user-images.githubusercontent.com/56165279/117686392-d1e24b00-b184-11eb-8bf6-f4e6b382a2bd.png)

## Supported Features 
+ Upload new image
  - title
  - image preview
  - text content
+ Edit existing image
  - reload existing content and image for editing
  - user authentication 
+ Delete image
  - delete and re-route to main page
  - user authentication 
+ User login
  - ID validation
  - password hasing
  - JSON web token
+ User logout
  - logout and re-route to main page

## How to Start 

+ Angular
/user_folder/ng serve

+ Node.js
/user_folder/npm run start:server

+ Web Browser
http://localhost:4200/

## How to use

### Browse
![image](https://user-images.githubusercontent.com/56165279/117686352-c7c04c80-b184-11eb-8826-c21986af3471.png)
  
1. Main page of the image repository. You can always return to the main page of the app with this button.
1. You can upload a new post
1. The button lets you fold the current post. then it only shows the title
1. you can edit the current post.
1. you can delete the current post. 
1. you can unfold the post.

### New Post
![image](https://user-images.githubusercontent.com/56165279/117688252-99dc0780-b186-11eb-8721-6565f0ef99de.png)

1. You need to fill the title
1. You can pick a photo from your Windows file explorer or MacOS finder. Once the photo is uploaded, it shows the preview of the image.
1. You can add any words for the photo
1. If you click the "Save Post" button, the page returns to the main page.

### Edit existing post

![image](https://user-images.githubusercontent.com/56165279/117689845-2affae00-b188-11eb-84d8-9794b4bb7cb9.png)

1. You can edit the post by choosing the EDIT button.
2. All the title and content is prefilled in the edit menu. You can change the photo with the "Pick Image" button.
3. Once the edit is finished, you can choose the "Save Post" button to finalize the edit. Once you click the button, the page returns to the main page.

### Delete existing post

![image](https://user-images.githubusercontent.com/56165279/117690854-4a4b0b00-b189-11eb-9d59-d8a7fdf3eb11.png)

1. Once you click the "DELETE" button, it instantly deleted, and the next post becomes the first post 

## Development Environment
1. Mongo DB
1. Express
1. Angular
1. NodeJS
1. Other libraries: nodemon, body-parser, mongoose, multer

