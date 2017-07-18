# Contraster
A before and after slider with zoom and pan functionality using Cocoen. *Currently in early development*

## Instuctions:
![](images/how_to_details.png)

In the cocoen-container ```<div>```, include the ```data-scale="x"``` attribute and specify the desired zoom distance. Each attribute is uinique to the current element.  
```
<div class="cocoen-container" data-scale="2">
  <div class="cocoen">
    <img src="image/path" alt="Before">
    <img src="image/path" alt="After">
  </div>
</div>
```
