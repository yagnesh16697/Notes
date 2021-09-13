# Node JS

### JavaScript Runtime

JS > V8(engine) + Libuv(in C++) > node

#### How do you run JS?

You need JavaScript runtime.

NodeJS is a java runtime built on Chrome's V8 JavaScript engine.

#### REPL(Read Eval Print Loop)

const cheer = "Wooh" + "hoo"

1. Reading the code & parsing the code.
2. Evalution.
3. Result will be printed.
4. Loop(it will continue untill we exit)

#### Node Vs JS

window global
document process  
history module
loaction \_\_filename()
navigator require()

#### What does node.js do?

V(8) + Node JS APIs(fs,http,path,crypto) + Node.JS binding + libuv

#### Asynchronous

Code that doesn't run line by line.

console.log("hello");
console.log("world");

##### Op

hello
world

setTimeout(() => console.log("hello"),1000);
console.log("world");

##### Op

world
hello

#### Non Blocking Code

blocking fun

- JSON.stringify();

non blocking function

- setTimeout
- readFIle

#### Is JavaScript is synchronous or Asynchronous?
