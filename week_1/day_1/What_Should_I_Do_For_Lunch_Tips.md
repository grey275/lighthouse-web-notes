### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
function whatToDoForLunch(hungry, availableTime) {
  if (!hungry) {
    console.log('Wait till you\'re hungry! Get back to work!');
    return;
  }
  if (availableTime < 20) {
    console.log('pick something up and eat it on campus!');
    return;
  }
  if (20 >= availableTime <= 30) {
    console.log('go eat out somewhere');
    return;
  }
  console.log('wait till later! you have work to do');
}
```