# Vladislav Kravchuk

## Contact information:

- Phone: +375333767404
- E-mail: krauchukvlad@gmail.com
- Telegram: [@harold_reevse](https://t.me/harold_reevse)
- LinkedIn: [www.linkedin.com/in/kravchuk-vladislav](www.linkedin.com/in/kravchuk-vladislav)
- GitHub: [https://github.com/kravchuk21](https://github.com/kravchuk21)

## About me:

I'm 16 years old and a Front-end React developer.

I have more than 4 years of experience developing websites and web applications on React. I've been working in freelance marketplaces for the last 2 years. I also have back-end development experience with Node.js and some mobile development with React Native.

My goal is to start my career as a junior Front-end React developer and grow to senior within 5 years.

## Technical skills:

- Front-end:
  - TypeScript, JavaScript(ES6+)
  - React, Next.js
  - Redux, Redux Toolkit, Redux Saga, Redux Thunk, Reselect
  - CSS, SCSS, styled-components, CSS Modules, PostCSS
  - HTML5
  - Webpack, Gulp, Vite
  - React Testing Library, Jest
  - ESLint, Prettier, EditorConfig
- Back-end:
  - Node.js NestJS, Express
  - MySQL, NoSQL
  - PHP
- Mobile:
  - React Native Cli / Expo
- Other skills:
  - Git, GitHub, GitLab
  - GitHub / GitLab CI/CD
  - Docker, Docker compose
  - Figma, Photoshop

## Code example:

React hook useHover

```javascript
import { useState, useEffect, useRef, MutableRefObject } from "react";

function useHover<T>(): [MutableRefObject<T>, boolean] {
  const [value, setValue] = useState < boolean > false;

  const ref: any = (useRef < T) | (null > null);

  const handleMouseOver = (): void => setValue(true);
  const handleMouseOut = (): void => setValue(false);

  useEffect(() => {
    const node: any = ref.current;
    if (node) {
      node.addEventListener("mouseover", handleMouseOver);
      node.addEventListener("mouseout", handleMouseOut);

      return () => {
        node.removeEventListener("mouseover", handleMouseOver);
        node.removeEventListener("mouseout", handleMouseOut);
      };
    }
  }, [ref.current]);

  return [ref, value];
}

export default useHover;
```

## Experience:

- **Freelance exchange**
  _2020 - 2022_
