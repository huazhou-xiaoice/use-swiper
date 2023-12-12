**IMPORTANT**: this is a minimalistic fork, the original url is [here](https://github.com/gaoljie/use-swiper).

# use-swiper

### Installation

#### yarn

`yarn add @zhouhua_rinna/use-swiper`

#### npm

`npm install @zhouhua_rinna/use-swiper`

#### include css

```js
import "@zhouhua_rinna/use-swiper/lib/swiper.min.css";
```

### Basic Usage

```tsx
import React from "react";
import useSwiper from "@zhouhua_rinna/use-swiper";

const App = () => {
  const { ref } = useSwiper();
  const list = [1, 2, 3, 4, 5];
  return (
    <div ref={ref}>
      {list.map(item => (
        <div key={item}>{item}</div>
      ))}
    </div>
  );
};
```
