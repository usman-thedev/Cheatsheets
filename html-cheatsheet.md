# Html Cheatsheet

---

### 1. Boilerplate
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Boilerplate</title>
</head>
<body>
    <h1>Hello world</h1>
</body>
</html>

```

### 2. Paragraph
```
<p>this is a paragraph </p>
```

### 3. Comments
```
<!-- this is a comment -->

<!--
    Or you can comment out a
    large number of lines.
-->
```

### 3. Headings
```
<h1> This is Heading 1 </h1>
<h2> This is Heading 2 </h2>
<h3> This is Heading 3 </h3>
<h4> This is Heading 4 </h4>
<h5> This is Heading 5 </h5>
<h6> This is Heading 6 </h6>
```

### 4. Link
```
<a href=" here comes the url ">QuickRef</a>
```

### 5. Images
```
<img loading="lazy" src="https://xxx.png" alt="Describe image here" width="400" height="400">

```

### 6. Text Formatting Tags
```
<b>Bold Text</b>
<strong>This text is important</strong>
<i>Italic Text</i>
<em>This text is emphasized</em>
<u>Underline Text</u>
<pre>Pre-formatted Text</pre>
<code>Source code</code>
<del>Deleted text</del>
<mark>Highlighted text (HTML5)</mark>
<ins>Inserted text</ins>
<sup>Makes text superscripted</sup>
<sub>Makes text subscripted</sub>
<small>Makes text smaller</small>
<kbd>Ctrl</kbd>
<blockquote>Text Block Quote</blockquote>
```

### 7. I-Frame
```
<iframe title="New York"
    width="342"
    height="306"
    id="gmap_canvas"
    src="https://maps.google.com/maps?q=2880%20Broadway,%20New%20York&t=&z=13&ie=UTF8&iwloc=&output=embed"
    scrolling="no">
</iframe>

```

### 8. Javascript 
```
<script type="text/javascript">
    let text = "Hello QuickRef.ME";
    alert(text);
</script>
```

### 9. CSS
```
<style type="text/css">
    h1 {
        color: purple;
    }
</style>
```

### 10. Document
```
<body>
  <header>
    <nav>...</nav>
  </header>
  <main>
    <h1>QuickRef.ME</h1>
  </main>
  <footer>
    <p>©2023 QuickRef.ME</p>
  </footer>
</body>
```

### 11. Header Navigation
```
<header>
  <nav>
    <ul>
      <li><a href="#">Edit Page</a></li>
      <li><a href="#">Twitter</a></li>
      <li><a href="#">Facebook</a></li>
    </ul>
  </nav>
</header>
```

### 12. Video
```
<video controls="" width="100%">
    <source src="https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
</video>
```

### 13. Audio
```
<audio controls
    src="https://interactive-examples.mdn.mozilla.net/media/cc0-audio/t-rex-roar.mp3">
    Your browser does not support the audio element.
</audio>
```

### 14. Ruby Tag
```
<ruby>
  汉 <rp>(</rp><rt>hàn</rt><rp>)</rp>
  字 <rp>(</rp><rt>zì</rt><rp>)</rp>
</ruby>
```

### 15. Progress Bar
```
<progress value="50" max="100"></progress>
```

### 16. Tabels
```
<table>
    <thead>
        <tr>
            <td>name</td>
            <td>age</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Roberta</td>
            <td>39</td>
        </tr>
        <tr>
            <td>Oliver</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

### 17. Un-ordered Lists
```
<ul>
    <li>I'm an item</li>
    <li>I'm another item</li>
    <li>I'm another item</li>
</ul>
```

### 18. Ordered List
```
<ol>
    <li>I'm the first item</li>
    <li>I'm the second item</li>
    <li>I'm the third item</li>
</ol>
```

### 19. Defination List
```
<dl>
    <dt>A Term</dt>
    <dd>Definition of a term</dd>
    <dt>Another Term</dt>
    <dd>Definition of another term</dd>
</dl>
```

### 20. Forms
```
<form method="POST" action="api/login">
  <label for="mail">Email: </label>
  <input type="email" id="mail" name="mail">
  <br/>
  <label for="pw">Password: </label>
  <input type="password" id="pw" name="pw">
  <br/>
  <input type="submit" value="Login">
  <br/>
  <input type="checkbox" id="ck" name="ck">
  <label for="ck">Remember me</label>
</form>
```

### 21. Input Tags
```
<label for="Name">Name:</label>
<input type="text" name="Name" id="">
```

### 22. Textarea Tags
```
<textarea rows="2" cols="30" name="address" id="address"></textarea>
```

### 23. Radion Buttons
```
<input type="radio" name="gender" id="m">
<label for="m">Male</label>
<input type="radio" name="gender" id="f">
<label for="f">Female</label>
```

### 24. Checkboxes
```
<input type="checkbox" name="s" id="soc">
<label for="soc">Soccer</label>
<input type="checkbox" name="s" id="bas">
<label for="bas">Baseball</label>
```

### 25. Select Tags
```
<label for="city">City:</label>
<select name="city" id="city">
    <option value="1">Sydney</option>
    <option value="2">Melbourne</option>
    <option value="3">Cromwell</option>
</select>
```

### 26. Fieldset
```
<fieldset>
    <legend>Your favorite monster</legend>
    <input type="radio" id="kra" name="m">
    <label for="kraken">Kraken</label><br/>
    <input type="radio" id="sas" name="m">
    <label for="sas">Sasquatch</label>
</fieldset>
```















