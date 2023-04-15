<!-- HTML -->
# Q1.
For the following table, which statement is true?
```html
<!DOCTYPE html>
<html>

<head>
  <title>Metro Vancouver Cities</title>
</head>

<body>
  <h1>Metro Vancouver Cities</h1>
  <table>
    <tr>
      <th>City</th>
      <th>Population</th>
      <th>Location</th>
    </tr>
    <tr>
      <td>Vancouver</td>
      <td>2,830,000</td>
      <td>49.2827° N, 123.1207° W</td>
    </tr>
    <tr>
      <td>Surrey</td>
      <td>527,000</td>
      <td>49.1044° N, 122.8011° W</td>
    </tr>
    <tr>
      <td>Burnaby</td>
      <td>239,000</td>
      <td>49.2421° N, 122.9939° W</td>
    </tr>
    <tr>
      <td>Richmond</td>
      <td>222,000</td>
      <td>49.1666° N, 123.1336° W</td>
    </tr>
    <tr>
      <td>Coquitlam</td>
      <td>151,000</td>
      <td>49.2731° N, 122.7642° W</td>
    </tr>
    <tr>
      <td>North Vancouver</td>
      <td>85,000</td>
      <td>49.3163° N, 123.0693° W</td>
    </tr>
    <tr>
      <td>Langley</td>
      <td>82,000</td>
      <td>49.1044° N, 122.6615° W</td>
    </tr>
    <tr>
      <td>Delta</td>
      <td>102,000</td>
      <td>49.0847° N, 123.0588° W</td>
    </tr>
  </table>
</body>

</html>
```
A. The table has 8 columns and 3 rows.  
B. The table has 8 rows and 3 columns.  
C. The table has 8 rows and 2 columns.  
D. The table has 8 columns and 2 rows.  

Answer: B

# Q2.
All the following color codes are for *Tomato* color except
 
B. `rgb(255, 99, 71)`  
C. `hsl(9, 100%, 64%)`  
A. `#FF6347`  
D. `#113347`  

Answer: D


# Q3.
All the following are attributes for the `<hr>` tag except:

A. `color`    
B. `type`  
C. `align`   
D. `noshade`     
E. `size`  

Answer: C

# Q4.
Inline elements typically do not initiate a new line in the document flow by default, whereas block elements usually cause a line break. However, it's important to note that this behavior can be altered using CSS, as is often the case with web page design.


A. True  
B. False  

Answer: A

# Q5.
The following are invalid syntax of a hyperlink that will direct users to the website `https://www.example.com` except

A. `<a>Visit Example Website</a>`  
B. `<a href="https://www.example.com">Visit Example Website</a`  
C. `<a href="https://www.example.com">Visit Example Website</a>`  
D. `<a href="example">Visit Example Website</a>`

Answer: C

<!-- CSS -->
# Q6.
Which of the following element will be colored in blue

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    h1+p {
      color: blue;
      font-size: 18px;
    }
  </style>
</head>

<body>

  <h1>Heading 1</h1>
  <p>Paragraph 1</p>
  <p>Paragraph 2</p>


</body>

</html>
```

A. Paragraph 1  
B. Paragraph 2  
C. Both Paragraph 1 and Paragraph 2  
D. Heading 1  
E. Heading 1 and Paragraph 1  

Answer: A


# Q7. 
For the following code, which statement is true?

```html
<style>
  /* Define the base font size for the body element */
  body {
    font-size: 10px;
  }

  /* Use em units for font size and margin */
  h1 {
    font-size: 2em;
    /* 2 times the font size of the parent (body) */
    margin-bottom: 1em;
    /* 1 times the font size of the parent (h1) */
  }

  p {
    font-size: 1.2em;
    /* 1.2 times the font size of the parent (body) */
    margin-bottom: 0.5em;
    /* 0.5 times the font size of the parent (p) */
  }
</style>

<body>
  <h1>Heading 1</h1>
  <p>Paragraph 1</p>
  <p>Paragraph 2</p>
</body>
```

A. The font size of the body element is 10px, the font size of the h1 element is 20px, and the font size of the p element is 14.4px.  
B. The font size of the body element is 10px, the font size of the h1 element is 12px, and the font size of the p element is 12px.  
C. The font size of the body element is 10px, the font size of the h1 element is 20px, and the font size of the p element is 12px.  
D. The font size of the body element is 10px, the font size of the h1 element is 12px, and the font size of the p element is 14.4px.  

Answer: C


# Q8. 
Which of the following is true about the above code?

```html
<style>
  /* Define the base font size for the root element */
  html {
    font-size: 16px;
  }

  body {
    font-size: 10px;
  }

  /* Use rem units for font size and margin */
  h1 {
    font-size: 2rem; /* 2 times the font size of the root (html) element */
    margin-bottom: 1rem; /* 1 times the font size of the root (html) element */
  }

  p {
    font-size: 1.2rem; /* 1.2 times the font size of the root (html) element */
    margin-bottom: 0.5rem; /* 0.5 times the font size of the root (html) element */
  }
</style>

<body>
  <h1>Heading 1</h1>
  <p>Paragraph 1</p>
  <p>Paragraph 2</p>
</body>

```

A. The font size of the root element is 16px, the font size of the body element is 10px, the font size of the h1 element is 32px, and the font size of the p element is 20px.  
B. The font size of the root element is 16px, the font size of the body element is 10px, the font size of the h1 element is 20px, and the font size of the p element is 19.2px.  
C. The font size of the root element is 16px, the font size of the body element is 10px, the font size of the h1 element is 32px, and the font size of the p element is 19.2px.  
D. The font size of the root element is 16px, the font size of the body element is 10px, the font size of the h1 element is 20px, and the font size of the p element is 20px.  

Answer: C


# Q9. 
Which of the following CSS box model is correct for the following code?


```html
<style>
  * {
    box-sizing: border-box;
  }

  /* Define styles for the box */
  .box {
    width: 200px;
    height: 100px;
    padding: 20px;
    border-width: 2px;
    border-style: solid;
    border-color: #000000;
    margin: 10px;
  }
</style>

<body>
  <div class="box">
    This is a box with content.
  </div>
</body>
```

A. ![](https://media.discordapp.net/attachments/1059741112715182130/1096478402522927257/image.png?width=299&height=199)  

B. ![](https://media.discordapp.net/attachments/1059741112715182130/1096478649315762176/image.png?width=282&height=194)  

C. ![](https://media.discordapp.net/attachments/1059741112715182130/1096478756085956690/image.png?width=272&height=195)  

d. ![](https://media.discordapp.net/attachments/1059741112715182130/1096478854807306250/image.png?width=306&height=209)  


Answer: A


# Q10.
How to design the following layout using Bootstrap
![](https://media.discordapp.net/attachments/1059741112715182130/1096483847522226287/image.png?width=1379&height=212)


A. 
```html

  <div class="container px-4 py-4">
    <div class="row gx-5">
      <div class="col col-md-4">
        <div class="p-3 border bg-light">Block</div>
      </div>
      <div class="col container ">
        <div class="row  ">
          <div class="col col-md-12">
            <div class="p-3 border bg-light">Block</div>
          </div>
          <div class="col col-md-12">
            <div class="p-3 border bg-light">Block</div>
          </div>
        </div>
      </div>
    </div>
  </div>
  ```

B. 
```html
 <div class="container px-4 py-4">
    <div class="row gx-5">
      <div class="col container ">
        <div class="row  ">
          <div class="col col-md-12">
            <div class="p-3 border bg-light">Block</div>
          </div>
          <div class="col col-md-12">
            <div class="p-3 border bg-light">Block</div>
          </div>
        </div>
      </div>
      <div class="col col-md-4">
        <div class="p-3 border bg-light">Block</div>
      </div>
    </div>
  </div>
  ```

Answer: B


<!-- JS -->
# Q11.

What is the output of the following code?


```js
const fruits = ['apple', 'banana', 'orange', 'grape'];

const x = fruits.slice(-2);

console.log(x); 
```

A. `[undefined, undefined]`  
B. `['banana', 'orange']`   
C. `['orange', 'grape']`    
D. `['apple', 'banana']`   

Answer: C. `['orange', 'grape`']

---

For the following JSON object, answer the next couple of questions

```js
const data = [
  {
    "name": "Italiano Ristorante",
    "cuisine": "Italian",
    "location": "123 Main St, New York",
    "rating": 4.5,
    "menus": [
      {
        "category": "Appetizers",
        "items": [
          "Bruschetta",
          "Garlic Bread",
          "Caprese Salad"
        ]
      },
      {
        "category": "Main Course",
        "items": [
          "Pasta Carbonara",
          "Chicken Parmesan",
          "Margherita Pizza"
        ]
      },
      {
        "category": "Desserts",
        "items": [
          "Tiramisu",
          "Cannoli",
          "Panna Cotta"
        ]
      }
    ]
  },
  {
    "name": "Sushi Sake",
    "cuisine": "Japanese",
    "location": "456 Elm St, Los Angeles",
    "rating": 4.2,
    "menus": [
      {
        "category": "Appetizers",
        "items": [
          "Edamame",
          "Gyoza",
          "Tempura"
        ]
      },
      {
        "category": "Sushi Rolls",
        "items": [
          "California Roll",
          "Spicy Tuna Roll",
          "Rainbow Roll"
        ]
      },
      {
        "category": "Nigiri",
        "items": [
          "Salmon Nigiri",
          "Tuna Nigiri",
          "Yellowtail Nigiri"
        ]
      }
    ]
  }
]
```

# Q12.
 how to print the *Appetizers* of the **Sushi Sake** restaurant?


A. 
```js
console.log(data[0].menus.find(menu => menu.category === 'Appetizers').items);
```

B. 
```js
console.log(data[1].menus.find(menu => menu.category === 'Appetizers').items);
```

C.  
```js
console.log(data[1].menus.map(menu => menu.category === 'Appetizers').items);
```

D. 
```js
console.log(data[0].menus.map(menu => menu.category === 'Appetizers').items);
```

Answer: B


# Q13.
how to print the names of the restaurants ?


A. 
```js
console.log(
  data[0].find({}, {name :1})
);
```

B. 
```js
console.log(
  data[0].map(restaurant => restaurant.name)
);
```

C.  
```js
console.log(
  data.map(restaurant => restaurant.name)
);
```

D. 
```js
console.log(
  data.find({}, {name :1})
);
```

Answer: C

# Q14.
Which statement is true about the following code?
```js
const fruits = ['apple', 'banana', 'orange', 'grape'];

fruits.unshift('strawberry');

```

A. The array `fruits` will be `['apple', 'banana', 'orange', 'grape', 'strawberry']`
B. The array `fruits` will be `['strawberry', 'apple', 'banana', 'orange', 'grape', 'strawberry']`
C. The array `fruits` will be `['apple', 'banana', 'orange', 'grape']`
D. The array `fruits` will be `['strawberry', 'apple', 'banana', 'orange', 'grape']`

Answer: D


# Q15.
Which statement is true about the following code?

```js
const fruits = ['apple', 'banana', 'orange', 'grape'];

fruits.splice(1, 2, 'watermelon', 'mango');

```

A. `['apple', 'watermelon', 'mango', 'orange', 'grape']`
B. `['apple', 'watermelon', 'mango', 'banana', 'orange', 'grape']`
C. `['apple', 'watermelon', 'mango', 'banana', 'grape']`
D. `['apple', 'watermelon', 'mango', 'grape']`

Answer: D

---
Use the following "weather" collection to answer the question below:

```json
[
  {
    "city": "New York",
    "country": "United States",
    "temperature": 22.5,
    "humidity": 60,
    "precipitation": 0.1,
    "windSpeed": 8,
    "conditions": ["sunny", "partly cloudy"],
    "updatedDate": "2023-04-06T10:30:00Z"
  },
  {
    "city": "London",
    "country": "United Kingdom",
    "temperature": 12.9,
    "humidity": 75,
    "precipitation": 0.3,
    "windSpeed": 12,
    "conditions": ["rainy", "windy"],
    "updatedDate": "2023-04-06T09:45:00Z"
  },
  {
    "city": "Sydney",
    "country": "Australia",
    "temperature": 26.7,
    "humidity": 50,
    "precipitation": 0,
    "windSpeed": 5,
    "conditions": ["sunny"],
    "updatedDate": "2023-04-06T08:15:00Z"
  }
]
```

```json
[
  {
    "city": "New York",
    "country": "United States",
    "temperature": 22.5,
    "humidity": 60,
    "precipitation": 0.1,
    "windSpeed": 8,
    "conditions": ["sunny", "partly cloudy"],
    "updatedDate": "2023-04-06T10:30:00Z"
  },
  {
    "city": "London",
    "country": "United Kingdom",
    "temperature": 12.9,
    "humidity": 75,
    "precipitation": 0.3,
    "windSpeed": 12,
    "conditions": ["rainy", "windy"],
    "updatedDate": "2023-04-06T09:45:00Z"
  },
  {
    "city": "Sydney",
    "country": "Australia",
    "temperature": 26.7,
    "humidity": 50,
    "precipitation": 0,
    "windSpeed": 5,
    "conditions": ["sunny"],
    "updatedDate": "2023-04-06T08:15:00Z"
  }
]

```

# Q16.

Using the MongoDB find method, retrieve all the weather data documents from the "weather" collection where the temperature is greater than or equal to 20°C and the conditions include "sunny".


A. 
```js
db.weather.find({ temperature: { $gte: 20 }, conditions: "sunny" })
```

B. 
```js
db.weather.find({ temperature: { $gte: 20 }, conditions: { $in: "sunny" } })
```

C. 
```js
db.weather.find({ temperature: { $gt: 20 }, conditions: "sunny" })
```

D.  
```js
db.weather.find({ temperature: { $gte: 20, $lt: 25 }, conditions: "sunny" })
```

Answer: A

# Q17.

Retrieve only the `city` and `temperature` fields for all the weather data documents from the weather collection where the `conditions` field is `rainy`.

A. 
```js
db.weather.find({ conditions: "rainy" }, { city: 1, temperature: 1 })
```

B.
```js
db.weather.find({ conditions: "rainy" }, { _id: 0, city: 1, temperature: 1 })
```

C.
```js
db.weather.find({ conditions: "rainy" }, { _id: 0, city: 0, temperature: 1 })
```

D.
```js
db.weather.find({ conditions: "rainy" }, { city: 0, temperature: 1 })
```

Answer: B


# Q18.

Which city will be retrieved for the following query

```js
db.weather.find({ "conditions": "sunny" }).skip(1).limit(2)
```

A. London  
B. Sydney  
C. New York  
D. None of the above  

Answer: B

Which city will be retrieved for the following query


```js
db.weather.find({ "temperature": { $gt: 20 } }).sort({ "humidity": -1 }).limit(1)
```

A. London  
B. Sydney  
C. New York  
D. None of the above  

Answer: C


# Q20. 
What is the output of the following
```js
db.weather.find({ "temperature": { $gt: 20 } }).count()
```

A. 1  
B. 2  
C. 3  
D. None of the above

Answer: 2