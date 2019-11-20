# Harish Reddy Vavilala - Spark - Challange

<h2>1. Start New Maven Project</h2>
Create a new project using Maven.
Go to the folder where you have all the git projects and open vs code there.
Open this parent folder in VS Code.
Click the VS Code Extensions icon. Verify you have the two required extensions. If not, install them.
Click the VS Code Explorer icon. From the menu, select:
View / Command Palette / Maven: Create Maven Project / archetype-quickstart-jdk8 / most recent version.
When the folder window opens, click your parent folder up at the top, click "Select Destination Folder".

<h2>2. Interactive Mode</h2>

groupId: edu.nwmissouri.harishreddyvavilala
artifactId: spark-challenge
version: HIT ENTER
package: HIT ENTER
Y: HIT ENTER


<h2>3. Code the project </h2>

Change directory into your new spark-challenge folder. Right-click and open your spark-challenge folder in VS Code.

Add a basic README.md. Use it to store your notes and commands.

When VS Code asks: "A build file was modified. Do you want to synchronize the Java classpath/configuration?" Answer "Always" to allow VS Code to generate these artifacts automatically.


<h2>4. Clean and compile </h2>

mvn clean
mvn compile
mvn assembly:single


<h2>5. Execute</h2>

java -cp target/spark-challenge-1.0.0-jar-with-dependencies.jar edu.nwmissouri.harishreddyvavilala.App "data.txt"

<h2> data.txt </h2>
I have used starting 2 pages of Highlander Protector Novel for data.






