## debounce-now

A tiny, zero-dependency debounce function for JavaScript and React. Useful for input handlers, API calls, and more.

---

## Install

```bash
npm install debounce-now
```

---

## Usage

```javascript
import debounce from 'debounce-now';

const log = debounce((text) => console.log(text), 300);

log('Hello');
log('World');
// Only "World" will be logged after 300ms
```

#### `Typescript Usage`
```typescript
debounce(fn: Function, delay?: number): Function
```
- `fn` – The function to debounce
- `delay` – Delay in milliseconds (default: 300)

---

## Features
- Runs a function after a short delay.
- Ignores fast repeated calls.
- Helps reduce extra work like API calls.
- Useful in input fields, scroll, and resize.
- You can set your own delay time.
- Very small and easy to use.

---

## Examples

- Search inputs
- Resize/scroll events
- Button click limiters