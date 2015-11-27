# sass-rem

A plugin for [sass](http://sass-lang.com/) that convent design size to rem which makes responsive develop easier.
A Pure css responsive adaptation solution.


## Install

Download the files (https://github.com/hodor-cn/sass-rem).

## Usage

Edit `_rem-config.scss` to fit your design size and target size.
Import `_rem.scss` to any scss file if you need use the `rem` function.
Import `_rem-reset.scss` once.

## Example

### SCSS

```scss

@import "./rem";
div{
    width: rem(20);
    margin-top: rem(-10);
    margin-left: - rem(10);
    font-size: rem(60);
}
```

### CSS

```css

div{
    width: 0.1rem;
    margin-top: -0.05rem;
    margin-left: -0.05rem;
    font-size: 0.3rem;
}
```


