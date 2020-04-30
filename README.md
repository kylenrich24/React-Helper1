# 🌀 React-Helper1 🌀

<img src="https://sunscrapers.com/blog/wp-content/uploads/2018/11/1__DOHv30w-0eI-Ysz5U47Yg.png" height=500 width=900>


<h2>🌀 JSX</h2>
<br>
<br>
&nbsp;✏️ &nbsp; javascript version of html, simulates the real DOM<br>
&nbsp;✏️ &nbsp; combination of html native elements and our own components<br>

```jsx
<div className="blue">   // html element; notice we use className and not class; class is reserved in js
  <Profile />   // react component
</div>
```

<br>
* Babel is also the one responsible for converting this to html. https://babeljs.io/

<br>
<h3>Inline Styling</h3>
<br>

```jsx
<div style={{ backgroundColor: 'red' }}> // { js variable { js object; camelCase; 
  Hello There
</div>
```
<br>
<br>

<h3>Referencing JS in JSX</h3>
<br>
We can put javascript expression in JSX by using `{ }` <br><br>

```jsx
const buttonText = "Click Me";

<button>
  {buttonText}
</button>
```
<br>

```jsx
const getButtonText = () => {
  return 'Click on me!";
}

<button>
  {getButtonText()}
</button>
```
