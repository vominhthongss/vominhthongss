```html
<!DOCTYPE html>
<html>
<head>
<style>
  @keyframes rotate {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }
  
  .donut {
    width: 100px;
    height: 100px;
    background-color: #e89f71;
    border-radius: 50%;
    position: relative;
    animation: rotate 5s linear infinite;
  }
</style>
</head>
<body>

<div class="donut"></div>

</body>
</html>
```
