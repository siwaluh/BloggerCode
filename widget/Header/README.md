# Blogger Widget Header

## How to use
1. Widget Tag
```
<b:widget id='Header1' locked='true' type='Header' version='2' visible='true'>
  <!-- Add Base Code Here -->
</b:widget>
```

2. Global Widget in markup
```
<b:defaultmarkup type='Header'>
  <!-- Add Base Code Here -->
</b:defaultmarkup>
```

## Widget Condition
1. Behind title and description - image
```
data:imagePlacement in {"REPLACE", "BEFORE_DESCRIPTION"}
```

2. Instead of title and description - title
```
data:imagePlacement not in {"REPLACE", "BEFORE_DESCRIPTION"}
```

3. Have description placed after the image
3.1. description
```
data:imagePlacement != "REPLACE"
```

3.2. behindImageStyle
```
data:imagePlacement == "BEHIND"
```