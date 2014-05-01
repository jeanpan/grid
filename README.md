##Grid

A simple responsive design grid layout. <br>
It's a 12 column based grid. 

#### how to use it ?

```html
<div class="container">
    <div class="row clearfix">
        <div class="col col-6"></div>
        <div class="col col-6"></div>        
    </div>
</div>
```

#### define by yourself !

set the column width & gutters in variable.scss

```css
/* column width ratio based on the mock container width */
$mock-container-width: 1210px;

/* column number */
$total-grid: 12;

/* absoluted gutters (px) */
$absolute-gutters: 20px;
```