## What does this do?

`ImageFlipper` lets you flip images horizontally or vertically.

## How to use

<sub>Why would you use this though !?!?!</sub>

In your app's `build.gradle`

```
dependencies {
    implementation 'com.rubiconsx.flipzeus:flipzeus:1.0.0'
}
```

## API 
<sub>Ha<sup>ha<sup>ha</sup></sup></sub>

To flip vertically

```
ImageView mImageView = (ImageView) findViewById(R.id.imageView);
ImageFlipper.flip(mImageView, FlipDirection.VERTICAL);
```

To flip horizontally

```
ImageView mImageView = (ImageView) findViewById(R.id.imageView);
ImageFlipper.flip(mImageView, FlipDirection.HORIZONTAL);
```

You can also pass `Drawable`s or even `Bitmap`s directly.

