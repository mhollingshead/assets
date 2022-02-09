*Raw files for use outside of github*

```javascript
const n = 5;
const hypercube = new NCube(n);

setInterval(() => {
  hypercube.rotate(1 / Math.PI**3);
  hypercube.edges.forEach(edge => draw(edge));
}, 20);
```
