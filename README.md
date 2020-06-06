# load-preview-image
Load and Preview Image File with HTML and Javascript


``` html
<form method="post" action="" enctype="multipart/form-data">
  <!-- Other Elements -->
  <input type="file" name="easyfile">
  <input type="submit" name="upload">
</form>
```


``` javascript
<script>
  var loadFile = function(event) {
    var output = document.getElementById('output');
    output.src = URL.createObjectURL(event.target.files[0]);
  };
</script>
</form>
```


