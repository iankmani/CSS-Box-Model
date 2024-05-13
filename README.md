# CSS BOX MODEL DOCUMENTATION   
## what is a CSS box model 

The CSS box model describes the design and layout of elements in HTML documents.  
The CSS box model is a container that contains multiple properties including borders, margins, padding, and the content itself. It is used to create the design and layout of web pages.

## CSS Box Model Overview  
 It consists of the following components:  
 1. **Content** - The actual content of the HTML element, such as text, images, or other media.  
 2. **Padding** -  The space between the content and the element's border. Padding adds internal spacing within the element.  

 ```css

 element {
    padding: 50px;
    padding: 50px 80px;
    padding: 50px 80px 50px 80px;
 }
 ```
 3. **Border** - A line / border surrounding the content and padding.  

```css    
element {
  border: 2px solid black; 
  border-width: 2px; 
  border-style: solid; 
  border-color: black; 
}
```
 4. **Margin** - The space between the border of the element.  

 ```css
 element {
    margin: 50px;
    margin: 50px auto;
    margin: 30px 50px;
    margin: 10px 20px 30px 40px;
 }  
 ```
 
 ## Box Model Properties:
 CSS provides several properties to control the dimensions and spacing of elements within the box model:  
 1. **Width** -Sets the width of the content area of the element.

 2. **Height** - Sets the height of the content area of the element.

 3. **Padding**  - Sets the Padding space around the content area.

 4. **Border** - Sets the border around the padding area.

 5. **Margin** - Sets the margin space around the border of the element.  

 ```css
 .myExample {
    width: 100px;
    height: 50px;
    padding: 20px;
    border: 2px solid blue;
    margin: 30px;
 }
 ```

 ## Box Sizing  

 By default, the *width* and *height* properties determine the size of the content area only. However, you can alter this behavior using the ***box-sizing*** property:

 - **box-sizing: content-box;** (Default): Specifies that the *width* and *height* properties apply to the content area only.

 - **box-sizing: border-box;**  Specifies that the width and height properties include the content, padding, and border areas.

 ```css
 element {
    box-sizing: border-box;
    box-sizing: content-box;
 }
 ```