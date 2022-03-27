---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: '#fff'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: true
# some information about the slides, markdown enabled
layout: cover
---

# Interview

---
layout: center
---

# About CSS

---

## How do you solve CSS problem ?

<br>
<br>
<br>

<v-click>

For example: [this problem](https://code.h5jun.com/zijak)

</v-click>

---
layout: center
---

# About JavaScript

---

## Talk about OOP in JavaScript?

---

## What is pure function?

---

## What is higher-order functions?

---
layout: center
---

# Abount React

---

## Question 1

```js
class User extends Component {
  constructor(props) {
    super(props);
    this.state = {
      fullName: props.firstName + ' ' + props.lastName
    };
  }
}
```

<br>

<v-clicks>

- Is there any problem in above code?
- If yes, how to solve?

</v-clicks>

---

## Question 2

```js {7-13,18-19}
class Counter extends Compoennt {
  constructor(props) {
    super(props);
    this.state = {count: 0};
    this.increment = this.increment.bind(this);
  }
  increment() {
    this.setState({ count: this.state.count + 1 })
    this.setState({ count: this.state.count + 1 })
    this.setState({ count: this.state.count + 1 })

    console.log(this.state.count)
  }
  render() {
    const { count } = this.state;
    return (
      <main className="Counter">
        <p className="count">{count}</p>
        <button onClick={this.increment}>Increment</button>
      </main>
    );
  }
}
```

<arrow v-click="1" x1="600" y1="295" x2="400" y2="295" color="#564" width="3" arrowSize="1" />
<arrow v-click="1" x1="600" y1="402" x2="400" y2="402" color="#564" width="3" arrowSize="1" />

---

## Question 3

Requirement: change browser tab title when counter changes.

<v-clicks>

- By class-based component
- By Hooks

</v-clicks>

---

## Question 4

What is Thunk?
