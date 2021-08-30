# :scroll: Front-End challenge Exercise 2
## :mount_fuji: Objetive
The objetive of this exercise is to create an input component with the follow features:
* I can see error state
* I can choose to disable input
* I can choose to have helper text
* I can choose to have an icon on the left or right (Use Google Icon and at least 5 variants)
* I can have different input sizes
* I can have different colors
* I can choose to have input take the width of the parent
* I can have multiline input like a textarea
* When I hover or focus, I can see visual indicators
* I can still access all input attributes

## :airplane: The way
I have developed these component using React as front-end framework

## :fuelpump: Features
### :triangular_flag_on_post: Error state
You can set up the error state by using the error property:
```
<Input error />
```
### :triangular_flag_on_post: Disable input 
You can set up the error state by using the disabled property:
```
<Input disabled />
```
### :triangular_flag_on_post: Helper text
You can set up the helper text state by using the help property:
```
<Input help="I am a help text" />
```

### :triangular_flag_on_post: Icon
You can set up an icon on the left or on the right by using startIcon / endIcon property and an icon name of [google icons](https://fonts.google.com/icons):
```
<Input endIcon="info" />
<Input startIcon="thumb_up_off_alt" />
```
### :triangular_flag_on_post: Sizes
You can choose between three different sizes with the size property. Allowed values: sm (small), md (medium), lg (large). When any value is gived, the default value for the size property is medium
```
<Input size="sm" />
<Input size="md" />
<Input size="lg" />
```
### :triangular_flag_on_post: Colors
You can choose between 5 differents themes for your input with the property theme. Allowed values: pastel, cool, forest, autum and default. When any value is gived, the default value for the size property is default
```
<Input theme="pastel" />
<Input theme="cool" />
<Input theme="forest" />
<Input theme="autum" />
<Input theme="default" />

```
### :triangular_flag_on_post: Parent Width
To choose the input to have the parent width you have to use the fullwidth property
```
<Input fullwidth/>
```
### :triangular_flag_on_post: Multiline
To have multiline input you have to use textarea property. Further, you can use the row tag to specify the number of rows (by default it is 10)
```
<Input textarea rows='5'/>
```
### :triangular_flag_on_post: Text
To set up the label text, you have to use the label tag
To set up the placeholder text, you have to use the placeholder tag
```
<Input label="my label" placeholder="my placeholder"/>
```

