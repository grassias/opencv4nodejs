# VideoCapture

<a name="constructors"></a>

## Constructors
``` javascript
VideoCapture : new VideoCapture(String filePath)
VideoCapture : new VideoCapture(Number devicePort)
```
## Methods

<a name="read"></a>

### read
``` javascript
Mat : cap.read()
```

<a name="readAsync"></a>

### readAsync
``` javascript
cap.readAsync(callback(Error err, Mat frame))
```

<a name="reset"></a>

### reset
``` javascript
cap.reset()
```

<a name="get"></a>

### get
``` javascript
cap.get(Int property)
```

<a name="set"></a>

### set
``` javascript
cap.set(Int property, Number value)
```

<a name="release"></a>

### release
``` javascript
cap.release()
```