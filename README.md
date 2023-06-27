```haskell
getOutput :: String
getOutput = "Mengapa persepektif logika semua orang demikian, sedangkan saya sebaliknya?"

printText :: String -> IO ()
printText text = putStrLn text

main :: IO ()
main = do
  let output = getOutput
  printText output
```
