# Wordpress Checklist
My Personal Wordpress Theme Development Checklist

# Table of Content
1. [Head](#head)
2. [Function](#function)
3. ~~[Body]()~~ *Coming Soon*
4. ~~[Footer]()~~ *Coming Soon*
5. ~~[Plug-ins]()~~ *Coming Soon*

# Head
- [ ] **DOCTYPE:** ![alt text](img/high-label.svg "High") Reference the browser to use HTML5
```html
<!doctype html> <!-- HTML5 -->
```

- [ ] **Charset:** ![alt text](img/high-label.svg "High") Declare charset. Reccomended charset: UTF-8
```html
<meta charset="utf-8">
```

- [ ] **Viewport:** ![alt text](img/high-label.svg "High") Declare viewport and responsive support
```html
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
```

# Function
- [ ] **title-tag:** ![alt text](img/high-label.svg "High") Theme support function to add `<title>` in `wp_head()`
```php
add_theme_support( 'title-tag' );
```
> * :book: https://codex.wordpress.org/Title_Tag

- [ ] **featured-thumbnail:** ![alt text](img/medium-label.svg "Medium") Theme support function to add post thumbnail
```php
add_theme_support( 'post-thumbnails' ); 
```
> * :book: https://codex.wordpress.org/Post_Thumbnails