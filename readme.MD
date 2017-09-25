# class 7: sneak peak of some css

### border 
~~~css
border: 1px solid salmon;
~~~
### outline 
~~~css
outline: 1px solid salmon;
~~~
`border` and `outline` both has same style `solid` `dotted` `dashed` so on

### text-align 
~~~css
text-align: center;
~~~
`text-align` value could be `left` `right` `center` `justify`. `justify` generally use in newspaper article.


### text-decoration 
~~~css
text-decoration: none;
~~~
`text-decoration` value could be `underline` `overline` `line-through` `none`

### text-transform 
~~~css
text-transform: uppercase;
~~~
`text-transforma` value could be `uppercase` `lowercase` `capitalize`

### text-indent 
~~~css
text-indent: 50px;
~~~
`text-indent` property is used to specify the indentation of the first line of a text. Generally to indent first letter of article paragraph


### letter-spacing
~~~css
letter-spacing: 3px;
~~~
how much space should be in between 2 letters

### word-spacing
~~~css
word-spacing: 3px;
~~~
how much space should be in between 2 words


### line-height
~~~css
line-height: 10px;
~~~
how much space should be in between 2 lines


### text-shadow
~~~css
text-shadow: 2px 3px 3px red;
~~~
Here `text-shadow` took 4 arguments. 
~~~css
text-shadow: horizontal-shadow vertical-shadow how-much-blur color;
~~~


### font-style
~~~css
font-style: normal;
~~~
common `font-style` is `normal` `italic`


### using icon
There are several icon library you will find online. Most used icon library is font-awesome. In order to use icon you have to import icon css library first then you can use appropriate css class to get expected icon'

linking css file:
~~~html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
~~~
e.g: Using facebook icon
~~~html
<i class="fa fa-facebook"></i>
~~~

### common pseudo selector
* `hover`
* `active`
* `focus`
* `visited`
* `before`
* `after`
* `nth-child`
* `first-child`
* `last-child`   
more pseudo class [w3schools](https://www.w3schools.com/css/css_pseudo_classes.asp)   
incase of `before` `after` pseudo selector you have to use `content` property.
~~~css
h1 {

}
h1:before {
  content:'tanim';
}
h1:after {
  content:'';

}

~~~
