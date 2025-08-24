# TravelAgency

# A Travel Agency Management System.

## Run Instructions (Windows)
1. **Download and install Java (17 or later) from [Adoptium](https://adoptium.net) or Oracle.**

2. **Download the latest JavaFX SDK for Windows.**
[Gluon JavaFX](https://gluonhq.com/products/javafx/)

3. **Extract it**
Example path: `C:\javafx-sdk-21\`

4. **Open Command Prompt / PowerShell**
   Navigate to the JAR file:
   ```powershell
   cd "C:\path\to\TravelAgency (Complete)"
5. Run with JavaFX libraries
java --module-path "C:\javafx-sdk-21\lib" --add-modules javafx.controls,javafx.fxml -jar TravelAgency.jar

Replace C:\javafx-sdk-21\lib with the actual path where you extracted JavaFX.






## Run Instructions (Linux)

1. **Install Java 17 or later**
   ```bash
   sudo apt install default-jdk openjfx

2. **Navigate to the project folder** 
cd "TravelAgency/TravelAgency (Complete)"

3. **Run the JAR with JavaFX**
java --module-path /usr/share/openjfx/lib \
     --add-modules javafx.controls,javafx.fxml \
     -jar TravelAgency.jar





