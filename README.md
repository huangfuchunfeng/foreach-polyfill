# foreach-polyfill

- A polyfill for NodeList.prototype.forEach and Array.prototype.forEach
- Array.forEach 在有些浏览器的兼容问题修复

## 使用说明

```javascript

<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="./dist/array-foreach-polyfill.min.js" /></script>
    <script>
      arrayForeach.polyfill()
    </script>
  </head>
  <body></body>
</html>

```

- 或者

```javascript
import { polyfill } './index.js'

polyfill()

```
