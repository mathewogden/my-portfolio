# Portfolio

## Table of Contents

- [Description](#Description)
- [Deployed Link](#Deployed-Link)
- [Technologies](#Technologies)
- [Code](#Code)
- [Author](#Author)
- [License](#License)

## Description

Hello! Welcome to my portfolio! Here you will find more about me and the work that I have done in the past enjoy!

## Deployed-Link

<!-- add deployed link in the paranthesis -->

- [Click Here](https://matogden.tech)

## Technologies

<!-- left examples here put edit to put your technologies -->

- [JavaScript](https://www.w3schools.com/js/)
- [ReactJs](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com)
- [Headless UI](https://headlessui.dev)
- [EmailJs](https://www.emailjs.com)
- [Netlify](https://www.netlify.com)

## Code

### Tailwind CSS

- Tailwind CSS was a new technology for me. I heard it was very flexible and that it would streamline my styling process and it did not disappoint!

* Installation if required

```
npm install -D tailwindcss
```

- Add the paths to all of your template files in your tailwind.config.js file.

```
module.exports = {
  purge: ['./src/**/*.{js,jsx,ts,tsx}', './public/index.html'],
  darkMode: false,
  theme: {
    extend: {},
  },
  variants: {
    extend: {},
  },
  plugins: [],
}
```

- Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

- Lastly, import your main CSS file in your main index.js file.

```
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';

ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
```

- Now get styling.

```
export default function Skills() {
    return (
        <section id="skills">
            <div className="container px-5 py-10 mx-auto">
                <div className="text-center mb-20">
                    <ChipIcon className="w-10 inline-block mb-4" />
                    <h1 className="sm:text-4xl text-3xl font-medium title-font text-white mb-4">
                        Skills &amp; Technologies
                    </h1>
                    <p className="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto">
                        Always working to reach the forefront of the ever-evolving tech landscape. Here's some languages and dev tools I quite enjoy.
                    </p>
                </div>
                <div className="flex flex-wrap lg:w-4/5 sm:mx-auto sm:mb-2 -mx-2">
                    {skills.map((skill) => (
                        <div key={skill} className="p-2 sm:w-1/2 w-full">
                            <div className="bg-gray-800 rounded flex p-4 h-full items-center">
                                <BadgeCheckIcon className="text-green-400 w-6 h-6 flex-shrink-0 mr-4" />
                                <span className="title-font font-medium text-white">
                                    {skill}
                                </span>
                            </div>
                        </div>
                    ))}
                </div>
            </div>
        </section>
    );
}
```

## Author

Mathew Ogden

<!-- add linnks to your social media -->

- [GitHub](https://github.com/mathewogden)
- [linkedIn](https://www.linkedin.com/in/mathew-ogden-b85688220/)
- [Instagram](https://www.instagram.com/matogden_/?hl=en)

## License]

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://www.mit.edu/~amini/LICENSE.md)
