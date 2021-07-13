# react-select-date
A React Component for choosing the single-date, multiple-date, range and slots booking.Purely date calculated from JavaScript Date Object.

Live Demo: ---Working on it---

![](https://user-images.githubusercontent.com/37235948/125201244-d6fa6e00-e28b-11eb-9761-4f0760ad357b.png)

![](https://user-images.githubusercontent.com/37235948/125206652-0027f800-e2a6-11eb-9fb5-2a7b219e9a5a.png)

# Getting Started

### Installation

Run `npm i react-select-date`

## Usage

### `SingelDate`
```javascript
import Calender from "react-select-date";

function MyComponent() {
  return (
      <Calender 
        onSelect={(date) => console.log(date)}
      />
  );
}

export default MyComponent;

```

### `DateRange`
```javascript
import Calender from "react-select-date";

function MyComponent() {
  return (
      <Calender 
        onSelect={(date) => console.log(date)}
        selectDateType="range"
        // select template color
        templateClr="blue"
      />
  );
}

export default MyComponent;

```

### `Multiple With DuelSlots`
```javascript
import Calender from "react-select-date";

function MyComponent() {
  return (
      <Calender 
        onSelect={(date) => console.log(date)}
        selectDateType="range"
        // select template color
        templateClr="blue"
      />
  );
}

export default MyComponent;

```

