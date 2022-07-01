# My Beautiful Gallery
Welcome to My Beautiful Gallery! This is a project in the context of the course "Desarrollo de aplicaciones web" (let's say, "full-stack development") by Netmind.

The aim is to create an app that works as a photo gallery where users can add images (not files but urls). Images are sorted by date, newest first; for every image there's some information such as a palette of 4 predominant colors in rgb, image size in Kb and width and height in pixels. It's possible to modify title and date and delete an image from the library. All changes are permanents, stored in a json file.

The app has been built in **node.js** with **express** and the views are rendered with **EJS**. **Tailwind CSS** has been a great help to manage CSS.

There are three validations at the moment of add a new image: 1- the image is not already in the "data base", 2- the url directs to a valid image (only urls starting with "http or https" and ending in ".jpg, .jpeg, .png or .webp") and 3- image size is maximum 500Kb. 

To install it just clone this repository and download the needed modules with

`npm install`

then run the app with

`npm start`
  





## Extra modules
[color-thief-node](https://www.npmjs.com/package/color-thief-node)": to get a color palette  
[image-url-validator](https://www.npmjs.com/package/image-url-validator)": to validate that the image directs to a valid image  
[probe-image-size](https://www.npmjs.com/package/probe-image-size)": to calculate image size before addition  

## Utils / Resources
[Tailwind Forms Plugin](https://github.com/tailwindlabs/tailwindcss-forms)  
[Hyper UI - Free Tailwind Components](https://www.hyperui.dev/)  
[Tailwind Toolbox - icons](https://www.tailwindtoolbox.com/icons)  
[Heroicons - Tailwind](https://heroicons.com/)  

Big thanks to @[Oscar Miras](https://github.com/omiras)





