# npm-module-detect-devices-hook
react Detect Devices hooks

example code:

```jsx
import logo from "./logo.svg";
import "./App.css";
import { handleDetectDevices } from "react-detect-devices-hook-joeban0608";
function App() {
  const { isMobile } = handleDetectDevices();

  return (
    <div className="App">
      isMobil?
      {` ${isMobile}`}
    </div>
  );
}

export default App;
```