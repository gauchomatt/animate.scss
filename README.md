# Animate.scss

This is a port of Dan Eden's [Animate.css](https://daneden.me/animate/) for SASS.

```
.your-class-name {
  @include bounceIn();
}
```

The mixin includes configurable options to customize the `delay`, `duration`, `function` and `fill-mode` of your animations.

```
.your-class-name {
  @include bounceIn(
    $duration: 1s,
    $delay: .2s,
    $function: ease, 
    $fill-mode: both
  );
}
```

## Licenses

Animate.css and Animate.scss are both licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Contributing

Thanks!