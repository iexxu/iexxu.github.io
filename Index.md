# Iexxu
Iexxu (formely Flueen during development) is a programming language based on python (probably localized python but with java like syntax)

# Example

```
import sys
import PyQt5.QtWidgets import QApplication, QWidget, QPushButton, QVBoxLayout

{
    public class FlueenApp {
        fn __init__(self) {
            # In Flueen, we still use standard Python logic for objects
            self.app = QApplication(sys.argv)
            self.window = QWidget()
            self.window.setWindowTitle("Flueen PyQt5 UI")
            self.window.resize(300, 200)

            self.layout = QVBoxLayout()
            
            self.btn = QPushButton("Click Me!")
            self.btn.clicked.connect(self.on_click)
            
            self.layout.addWidget(self.btn)
            self.window.setLayout(self.layout)
        }

        fn on_click(self) {
            print("Button clicked inside Flueen Class!")
            self.btn.setText("Clicked!")
        }

        fn run(self) {
            self.window.show()
            sys.exit(self.app.exec_())
        }
    }
}

# Execution logic
myapp = FlueenApp()
myapp.run()
```

# Installing
Windows
(Download the .exe or .msi installer from the releases and install it thats it)
Linux/Mac
Download the .tar.gz package from the releases and extract it and execute

```
dos2unix ./iexxulin
```

or

```
dos2unix iexxulin
```

chmod it and run

```
./iexxulin
```

and thats it your done

# Credits
This is a solo project from an dev who wants to private their info but can see their name in the MSI Installer or exe
