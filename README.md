# Random Poems API

## Overview
The Random Poems API provides developers with a rich collection of poems that can be used for educational projects, literary applications, or creative endeavors. With this API, you can fetch random poems along with details like the title, author, and content.

---

## Features
- **Fetch Random Poems**: Retrieve random poems with their full content.
- **Search**: Get details such as the poem's title and author.
- **Author List**:get list of all authors.

---

## Use Cases
- **Creative Writing Tools**: Inspire writers by providing random poems.
- **Educational Apps**: Use poems for teaching literature or poetry analysis.
- **Literary Projects**: Integrate poetry into applications for readers and enthusiasts.

---

## How to Get Started

### Prerequisites
- A RapidAPI account.
- An active subscription to the Random Poems API.

### Steps to Access the API

1. **Sign Up on RapidAPI**
   - Go to [RapidAPI](https://rapidapi.com/robotfa-robotma/api/random-poems) and create an account.

2. **Subscribe to the API**
   - Search for "Random Poems API" and subscribe to it.

3. **Get Your API Token**
   - Navigate to the "Endpoints" section of the API page on RapidAPI.
   - Copy your unique API key (token) provided in your account dashboard.

4. **Use the API**
   - Use the API key to authenticate your requests. Below is an example request:

     ```bash
     curl -X GET "https://random-poems.p.rapidapi.com/random" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: random-poems.p.rapidapi.com"
     ```

---

## Example API Endpoints

### 1. Get a Random Poem
Retrieve a random poem:
```bash
GET /random
```
**Response Example:**
```json
{
  "title": "The Road Not Taken",
  "author": "Robert Frost",
  "content": "Two roads diverged in a yellow wood, ..."
}
```

### 2. Search for Poems by Author
Fetch poems by a specific author:
```bash
GET /author/
```
**Response Example:**
```json
[
  {
    "title": "Stopping by Woods on a Snowy Evening",
    "author": "Robert Frost",
    "content": "Whose woods these are I think I know, ..."
  }
]
```


---

## Contribution
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or new features.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

