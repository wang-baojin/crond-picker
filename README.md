# crond-picker
crondate  parser formatter and ui picker 

## install
`npm i crond-picker`

## usage
```tsx
import { CrondPicker } from 'crond-picker'
import * as React from 'react'
import * as ReactDOM from 'react-dom'

ReactDOM.render(<CrondPicker value="* 30-59/2 * * *" onChange={crondStr => console.log(crondStr)} />, container)
```

Demo: [https://codesandbox.io/s/stoic-sound-oq6w3?file=/src/App.js](https://codesandbox.io/s/stoic-sound-oq6w3?file=/src/App.js)
