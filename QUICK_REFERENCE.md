# ES6+ Quick Reference Guide

## 🚀 Modern JavaScript Cheat Sheet

### Variables
```javascript
// Block-scoped variables
let name = 'Yassir';
const age = 25;
```

### Arrow Functions
```javascript
// Concise syntax
const greet = (name) => `Hello, ${name}!`;
const add = (a, b) => a + b;
```

### Template Literals
```javascript
// String interpolation
const message = `Welcome, ${name}! You are ${age} years old.`;
```

### Destructuring
```javascript
// Array destructuring
const [first, second] = ['React', 'Vue'];

// Object destructuring
const {name, email} = user;
```

### Spread & Rest
```javascript
// Spread operator
const newArray = [...oldArray, newItem];

// Rest parameters
const sum = (...numbers) => numbers.reduce((a, b) => a + b);
```

### Classes
```javascript
class Developer {
  constructor(name) {
    this.name = name;
  }
  
  code() {
    return `${this.name} is coding!`;
  }
}
```

### Promises & Async/Await
```javascript
// Promise
const fetchData = () => {
  return new Promise(resolve => {
    setTimeout(() => resolve('Data loaded'), 1000);
  });
};

// Async/Await
const getData = async () => {
  const data = await fetchData();
  console.log(data);
};
```

### Modules
```javascript
// Export
export const helper = () => 'Helper function';
export default MyComponent;

// Import
import MyComponent, { helper } from './module';
```

---

**Created by Yassir Rzigui (@yazzy01) - Full-Stack Developer & JavaScript Educator**
