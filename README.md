# Reactjs Media

##### <div align="center"> [![License: MIT](https://flat.badgen.net/npm/license/reactjs-media)](https://opensource.org/licenses/MIT) [![Npm package total downloads](https://flat.badgen.net/npm/dt/reactjs-media)](https://npmjs.com/package/reactjs-media) [![version](https://flat.badgen.net/npm/v/reactjs-media)](https://npmjs.com/package/reactjs-media) [![](https://flat.badgen.net/badge/icon/github?icon=github&label&color=black)](https://github.com/jim-junior/reactjs-median) </div>

The reactjs media is a react package with awesome HTMLMediaElements that are recreated into react components with a good looking UI and fast UX.

Try it out on [CodeSandbox](https://codesandbox.io/p/sandbox/reactjs-media-c5x795)

It includes currently only has a video and audio component.

Available components:

- Video
- Audio

#### Installation

To install go to your terminal and run this script

```bash
# npm
$ npm install reactjs-media
# yarn
$ yarn add reacttjs-media
```

If your see no error then is is Installed.

#### Setup

In here we shall show a small demo on how to setup a simple video component. We shall create the default component.


```jsx
import React from 'react';
import { Video } from 'reactjs-media';

const App = () => {
    return (
        <div>
            <MyVideo />
        </div>
    )
}

const MyVideo = () => {
    return (
        <>
        <div>
            <Video
                src='https://www.example.com/myvideo.mp4'
                poster='/poster.png'
            />
        <div/>
        </>
    )
}

```

If you want to learn more, Checkout the offical [Documentation](https://open.cranom.cloud/reactjs-media/intro "Documentation")

___

The source code can be found on [Github](https://github.com/jim-junior/reactjs-media).
