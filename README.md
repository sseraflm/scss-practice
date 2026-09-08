# scss-practice

### Variables

Variables store a reusable value, declared with `$`

```scss
$primary-color: #000080;
```

### Nesting

Lets you write selectors inside other selectors, matching your HTML structure. You can use `&` to target the parent.

### Mixins

`@mixin` groups reusable CSS, inserted with `@include`. can take parameters.

```scss
@mixin colorStyle($color, $bg-color: white) {
  color: $color;
  background-color: $bg-color;
}
```

### Extend and placeholder selectors

`@extend` lets a selector inherit properties from another it combines selectors into one rule which mean smaller outpus when properties are identical.