
# Object to Array in JS

convert objects to arrays with built in methods in javascript.


## Usage/Examples

```javascript
let myObject = {
    '00' : 'apple',
    '01' : 'banana',
    '02' : 'cherry',
    '03' : 'Dragonfruit'   
}
```


## Extract only Keys from Object to Array

```javascript
let onlyKeys = Object.keys(myObject)

console.log(onlyKeys) //['01','02','03','04']
```


## Extract only Values from Object to Array

```javascript
let onlyValues = Object.values(myObject)

console.log(onlyValues) //['apple','banana','cherry','Dragonfruit']
```


## Extract both Keys and Values from Object to Array

```javascript
let both = Object.entries(myObject)

console.log(both) //[['00','apple'],['01','banana'],['02','cherry'],['03','Dragonfruit']
```

