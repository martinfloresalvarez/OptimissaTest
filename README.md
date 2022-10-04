# OptimissaTest

### Swift Package Dependencies 

https://github.com/realm/SwiftLint.git
 
Targets -> Build Phases -> Run Swiftlint Script -> + Add new build Phases

```swift
export PATH="$PATH:/opt/homebrew/bin"
if which swiftlint > /dev/null; then
  swiftlint
else
  echo "warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint"
fi
```
este framwork es solo para las buenas practicas de codificación  
