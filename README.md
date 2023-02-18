
# SAVARI - Your Travel Companion

SAVARI is you travel Companion which help you to plan your nect travel efficiently and effectively. It helps you to book your preferred mode of travel.


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform
- Responsive web design : 
    - Responsive images for different cropping situations

- Support for legacy browsers:
    Use picturefill as a responsive image polyfill
    Test browser support for SVGs and flexbox with gulp-modernizr
    Convert SVGs to PNGs with gulp-svg2png
    Reveal page contents on scroll

- Smooth page scroll to an anchor on the same page

## Installation

#### Clone or download this repository

```bash
    git clone https://github.com/aishii/savari.git
```

### Software required

- [Python](https://www.python.org/downloads/)
 _Click on the link to download python_
    

- [PIP](https://pip.pypa.io/en/stable/installation/)

```bash
    python get-pip.py
```

- [Django](https://docs.djangoproject.com/en/4.1/topics/install/)
```bash
    python -m pip install Django
```

- [Xampp](https://www.apachefriends.org/download.html)
_Go to above link and download Xampp to run the application_

- [VS Code](https://code.visualstudio.com/) or any IDE of your choice
## Run Locally

- Open Xampp control panel and start Apache server and My SQL server
- Open VS code and import the cloned folder inside IDE

#### DB migration for intial setup and run

    py manage.py
after migration is done, 
- Run program using
```
    $ py main.py
```


## API Reference

#### Get all booking

```http
  GET /api/booking
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get booking by id

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 🚀 About Me
I'm a full stack _.net_ developer...


## Acknowledgements

- Kuldeep my best man of course always uwu.
other stuff like stackoverflow w3schools youtube who cares
