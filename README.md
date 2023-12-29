# Asian Kitchen's Menu

Welcome to the repository for the Asian Kitchen's Menu website! This simple website showcases a menu of delicious Asian dishes from Korea, Japan, and China. Users can filter the menu by cuisine type using interactive buttons.

## Table of Contents
- [Preview](#preview)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Menu Data](#menu-data)
- [Contributing](#contributing)
- [License](#license)

### Preview

![asianKitchenMenu](https://user-images.githubusercontent.com/56386597/234825388-463cc453-0063-4ec4-a231-981a5a585ca9.gif)

### Technologies Used
HTML
CSS
Bootstrap 5.0.0-beta1
JavaScript

### How to Use
1. Clone the repository to your local machine: <br>
  ```
    git clone https://github.com/your-username/AsianKitchenMenu.git
  ```
2. Open the index.html file in your preferred web browser.
3. Explore the Asian Kitchen's menu and filter dishes by cuisine type using the provided buttons.

### Menu Data
The menu data is stored in the script.js file as an array of objects. Each object represents a dish with the following properties:

- id: Unique identifier for the dish.
- title: Name of the dish.
- category: Cuisine type (e.g., Korea, Japan, China).
- price: Price of the dish.
- img: Path to the image of the dish.
- desc: Description of the dish.

Feel free to modify the menu by adding, removing, or updating dishes in the menu array.
```
const menu = [
    // ... (menu items)
];
```

### Contributing
If you'd like to contribute to the project, follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix: git checkout -b feature-name.
- Make your changes and commit them: git commit -m 'Description of changes'.
- Push your changes to your fork: git push origin feature-name.
- Create a pull request.

### License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for your own projects.
