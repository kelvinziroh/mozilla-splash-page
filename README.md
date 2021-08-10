# Mozilla Splash Page

This is an **MDN Front-end web developer** exercise on *Responsive images using html*.

The exercise focuses on  *html techniques* like:

## Resolution switching with different image sizes

Example:

```
<img srcset="firefoxlogo120.png 120w,
             firefoxlogo400.png 400w"
     sizes="(max-width: 500px) 120px,
                        400px"
     src="firefoxlogo400.png"
     alt="Firefox logo">
```

## Art direction 

Example:

```
<picture>
    <source media="(max-width: 600px)" srcset="red-panda600.jpeg">
    <source media="(min-width: 600px)" srcset="red-panda1200.jpeg">
    <img src="red-panda1200.jpeg" alt="A Picture of a Red Panda">
</picture>
```

