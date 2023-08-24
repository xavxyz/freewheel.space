https://konvajs.org/ ?

À retourner :

- https://codepen.io/xavxyz/pen/xmmjXQ/3b31eb25ad130f90d9dff225a4387141
- https://codepen.io/xavxyz/pen/JmrqWM/74b37ae54fea6a76d42dbf8f3a9a73bb
- et tous les autres

À explorer :

- https://pyramid-space.simple.ink/ -> generation avec NextJS

À détourner :

- https://codepen.io/sdras/pen/gWWQgb
- https://codepen.io/sdras/pen/RZGqxR + https://github.com/xavxyz/ecliptic-calendar
- https://github.com/xavxyz/nextjs-page-transitions

### Notes

```js
// Simplicity
function spinZ() {
  for (let v of vertices) {
    let dx = v.x - cx;
    let dy = v.y - cy;
    let x = dx * Math.cos(angle) - dy * Math.sin(angle);
    let y = dx * Math.sin(angle) + dy * Math.cos(angle);
    v.x = x + cx;
    v.y = y + cy;
  }
}
```
