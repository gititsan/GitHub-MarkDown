# Learning GitHub MarkDown
# h1 Tag ==> '#' 
## h2 Tag  ==> '##' 

This a paragraphe . To have the next paragraph writen in the next line Hit Enter.

This is my second Paragraph in the next Line.

- To have a list we use `-` or   `+`
+ Second List element
  
  + Two spaces before `-`  : will give us a second level List
     1. Level 3 using Numbers
  
## Adding Links 

[This is the description of my link](https://www.youtube.com/watch?v=eJojC3lSkwg)

To Write some code we use back ticks : `<div></div>`

To write a block of code we use Three back ticks :

```Javascript
export class ShoppingServiceService {
  IngrediantChange= new EventEmitter<Ingredient[]>();
  ingredients: Ingredient[] = [
    new Ingredient('Apples', 5),
    new Ingredient('Tomatoes', 10),
  ];
  constructor() { }


  onAdd(ingredient: Ingredient) {
    this.ingredients.push(ingredient);
    this.IngrediantChange.emit(this.ingredients);
  }

  getIng ()
  {
    return this.ingredients.slice();
  }
  ```

  N.B : `Dont Forget to use the type of the language after the first Three back tick so it can know which language and use its specific heighlights.`

## How To use images
Very Simillar To links we just write `![alt Text ](https://picsum.photos/200/300)`

  ![alt Text ](https://picsum.photos/200/300)

## Block quote

>Here is block quote

## Tables

They are supported by Github and other renderring websites

|Heading | Heading | Heading |
| --- | ---| --- |
|Content | Content | Content |
|Content | Content | Content |

This is a bold **Text** and an italic *Text*.

Bold ==> `** Text **`

Italic ==> `* Text * `

Crossed word ==> ~~No worries~~ ==> `~~No worries~~ `

### For more details on Markdown Visit this link : [Markdown Cheat Sheet ] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)




