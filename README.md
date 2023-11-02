           PHASE-1  
           
Design thinking is a creative problem-solving approach that can be applied to
designing an air quality monitoring system. Here's a simplified design thinking process
tailored to this task:
1. Empathize:
• Understand the needs and concerns of potential users, such as individuals,
communities, or organizations.
• Conduct interviews, surveys, and research to gather insights into air quality
issues and user preferences.
2. Define:
• Clearly define the problem and set specific goals for the monitoring system.
• Create user personas and scenarios to illustrate who will use the system and
in what contexts.
• Identify key challenges and constraints, such as budget limitations or technical
requirements.
3. Ideate:
• Brainstorm creative solutions for the air quality monitoring system.
• Encourage diverse perspectives from a cross-functional team.
• Explore different concepts, such as portable sensors, real-time data
visualization, or community engagement features.
4. Prototype:
• Build a low-fidelity prototype of the monitoring system. This could be a paper
sketch, a digital mockup, or a simple working model.
• Test the prototype with potential users to gather feedback on usability and
functionality.
• Iterate on the design based on user feedback and insights.
5. Test:
• Develop a more advanced prototype or a pilot version of the monitoring
system.
• Conduct user testing in real-world environments to assess its performance
and usability.
• Gather feedback and data on how well the system meets users' needs.
6. Implement:
• Based on the feedback and insights gathered during testing, refine the design
and create a production-ready version of the system.
• Collaborate with engineers, developers, and manufacturers to bring the
system to life.
• Ensure it meets quality standards and safety regulations.
7. Evaluate:
• Continuously monitor the air quality monitoring system's performance and
gather user feedback after it's deployed.
• Make improvements and updates based on user experiences and emerging
technologies.
• Measure the system's impact on improving air quality awareness and taking
appropriate actions.
8. Iterate:
• Design thinking is an iterative process. Use the insights gained from ongoing
evaluations to refine and enhance the system over time.

PHASE 2 - INNOVATION 

The creation and innovation of air quality monitoring systems have evolved
significantly over the years. Initially, air quality monitoring involved manual
sampling and analysis of air pollutants, but technological advancements have
revolutionized this field.
Key developments include:
 Sensor Technology:
Miniaturized and cost-effective air quality sensors have been developed,
allowing for real-time monitoring of various pollutants, such as particulate
matter (PM), volatile organic compounds (VOCs), and gases like nitrogen
dioxide (NO2) and ozone (O3).
 IoT Integration:
These sensors are often connected to the Internet of Things (IoT) platforms,
enabling remote data collection, analysis, and reporting. This connectivity
enhances the accessibility of air quality information.
 Mobile Apps and Websites:
Many air quality monitoring systems offer user-friendly mobile apps and
websites that provide real-time air quality data, historical trends, and health advisories. These tools empower individuals to make informed decisions
about outdoor activities.
 Data Analytics:
Advanced data analytics and machine learning algorithms are used to
interpret and predict air quality patterns. This helps authorities and
researchers identify pollution sources and formulate effective mitigation
strategies.
 Wearable Devices:
Innovations in wearable technology have led to the development of
personal air quality monitors that individuals can carry with them. These
devices provide real-time exposure information, promoting personal health awarness
 Air Quality Index (AQI):
The introduction of standardized AQI systems simplifies the communication
of air quality information to the public. It categorizes air quality into easyto-understand levels, making it more accessible to a wider audience.
 Environmental Regulations:
The innovation of air quality monitoring systems has been driven by the
need to comply with environmental regulations and standards.
Governments and organizations are increasingly investing inadvanced
monitoring infrastructure.
 Satellite and Remote Sensing:
Satellite technology and remote sensing techniques play a crucial role in
monitoring air quality on a regional or global scale. These tools provide
valuable data for understanding long-term trends and global air quality patterns.
 Crowdsourced Data:
Citizen science initiatives and crowdsourced data collection apps allow
individuals to contribute air quality measurements, expanding the coverage
of monitoring networks.
Innovations in air quality monitoring systems continue to evolve, driven by thegrowing awareness of the health impacts of air pollution and the need for
accurate, real-time information to support public health and environmental policies

        PHASE 3 - PROJECT DEVELOPMENT
        
Developing an air quality monitoring project using Tinkercad is a great way to learn
about environmental monitoring and IoT (Internet of Things) applications.. Here's a stepby-step guide to creating an air quality monitoring project using Tinkercad:
COMPONENTS :
1. Arduino board (e.g., Arduino Uno)
2. Gas sensors (e.g., MQ series for CO2, CO, or other gases)
3. DHT22 or DHT11 temperature and humidity sensor
4. Breadboard and jumper wires
5. Display (LCD or LED) or a computer screen for data visualization
6. A Wi-Fi module (e.g., ESP8266) for wireless data transmission (optional)
PROCEDURE :
1. Set up Tinkercad :
 Create an account on Tinkercad if you don't have one.
 Start a new circuit project.
2. Design the Circuit :
 Add the Arduino board to your circuit.
 Connect the gas sensors and DHT22/DHT11 sensor to the Arduino using
jumper wires.
 If you're using a display, add it to the circuit and connectit to the Arduino as
well.
 If you want to implement wireless data transmission, add an ESP8266 module and connect it to the Arduino.
3. Write the Arduino Code :
 Develop an Arduino sketch (code) that reads data from the gas sensors and the
temperature/humidity sensor.
 Calculate air quality index based on the sensor readings.
4. Simulate the Circuit :
 Use Tinkercad's simulation feature to test your circuit and code. Make sure the
sensor readings and displays work as expected.
5. Calibration :
 Calibrate your gas sensors if needed to ensure accurate air quality
measurements. This often involves exposing the sensors to known gas concentrations6. Data Visualization :
 If you are transmitting data to a server, set up a way to visualize the data using
a web interface or dashboard.
7. Testing :
 Test your project thoroughly in the simulation environment to ensure it's functioning correctly.
8. Real-world Implementation :
 Once your project works in the Tinkercad simulation, build the physical circuit
using real components.
 Upload the code to your Arduino board.
 Install the sensors in the desired location to monitor air quality.
9. Monitoring and Maintenance :
 Regularly monitor and maintain your air quality monitoring system.
 Address any issues or recalibrate sensors if necessary.

 PHASE-4      PROJECT DEVELOPMENT
 
Developing an air quality monitoring project using Tinkercad is a great way
to learn about environmental monitoring and IoT (Internet of Things)
applications.. Here's a coding and screenshots of stimulation of air quality
monitoring project using Tinkercad:
CODING :
/*
Air Monitoring System
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
The project's objective is to design a simple system that is used for simulating an Air Monitoring System using
Arduino Uno Board, Gas Sensor, Buzzer, LCD display, LEDs.
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
This sketch is used for Air-Monitoring.
The LCD prints "Harmful Gas is Detected", the Buzzer will generate an alarm sound, and the RED LED will be turned
on when the Gas Sensor detects a harmful gas in its reading range.
The Buzzer will be turned off and the GREEN LED will be turned on when the Gas Sensor does not detect any
harmful gases in its reading range.
The Circuit Connections:
-LCD:
* LCD RS pin to digital pin 12
* LCD Enable pin to digital pin 11
* LCD D4 pin to digital pin 5
* LCD D5 pin to digital pin 4
* LCD D6 pin to digital pin 3
* LCD D7 pin to digital pin 2
* LCD R/W pin to ground
* LCD VSS pin to ground
* LCD VCC pin to 5V
* wiper to LCD VO pin (pin 3)
-Gas Sensor:
* Gas Sensor Analog read pin to analog pin A0
-Buzzer:
* Buzzer pin to digital pin 8
-LEDs:
* Green LED pin to digital pin 6
* Red LED pin to digital pin 7
*/
// include the library code:
#include <LiquidCrystal.h>
// initialize the library with the numbers of the interface pins
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);
int sensor = A0;
int val = 0;
int limit = 40;
void setup() {
 Serial.begin(9600);
 // declaring LEDs pins as OUTPUTS Pins and turned them off at the beginning.
 pinMode(7, OUTPUT);
 pinMode(6, OUTPUT);
 digitalWrite(6, LOW);
 digitalWrite(7, LOW);
 // set up the LCD's number of columns and rows:
 lcd.begin(16, 2);
 // Print a message to the LCD.
 lcd.print("Air Monitoring");
 lcd.setCursor(0, 1);
 lcd.print("System");
 delay(500);
 lcd.clear();
}
void loop() {
 val = analogRead(sensor); // Initialize the value of (val) Variable with the Gas Sensor Reading.
 val = map(val, 306, 750, 0, 100); //Mapping the output voltage values from the Gas Sensor to values in the range
from 0 to 100.
 Serial.println(val); //Printing the Gas Sensor Reading in the Serial Monitor.
//If a harmful gas is detected.
 if (val > limit) {
 lcd.setCursor(0, 0);
 lcd.print("Harmful Gas is"); //Print a message to the LCD.
 lcd.setCursor(0, 1);
 lcd.print("Detected");
 digitalWrite(7, HIGH); //The Red LED wil be turned ON.
 digitalWrite(6, LOW); //The Green LED wil be turned OFF.
 tone(8, 1000); //The Buzzer will generate an alarm tone.
 delay(100); //Sound ON for 100 msec.
 noTone(8);
 delay(100); //Sound OFF for 100 msec.
 }
 else {
 lcd.clear(); //Clear the warning message from the LCD.
 noTone(8); //Sound OFF.
 digitalWrite(7, LOW); //The Red LED wil be turned OFF.
 digitalWrite(6, HIGH); //The Green LED wil be turned ON } }

        PHASE 5 : PROJECT DOCUMENTATION &SUBMISSION
  
Creating an air quality monitoring project using Arduino and Tinkercad is a great way to
simulate and prototype your system.
PROJECT OBJECTIVE :
1. Real-time Air Quality Monitoring :
 Develop a system that can continuously monitor key air quality
parameters such as particulate matter (PM2.5 and PM10), carbon dioxide (CO2),
carbon monoxide (CO), ozone (O3), nitrogen dioxide (NO2), temperature,
humidity, and air pressure.
2. Data Collection and Logging :
 Create a data acquisition system to collect and log air quality data at
regular intervals, ensuring data integrity and accuracy.
3. Visualization and User Interface :
 Develop a user-friendly interface for visualizing the collected data in realtime, allowing users to easily interpret air quality information.
4. Alerts and Notifications :
 Implement an alert system that can notify users when air quality levels
exceed predefined thresholds. These alerts can be in the form of visual indicators
or notifications sent to a user's device.
5. Historical Data Storage :
 Store historical air quality data for analysis, trend identification, and
comparison over time.
6. Data Analysis and Reporting :
 Utilize data analysis techniques to identify trends, correlations, and
potential sources of air quality issues. Generate periodic reports or visualizations
to help users understand long-term air quality patterns.
7. Remote Access :
 Enable remote access to the system, allowing users to monitor air
quality from anywhere using a web or mobile application.
8. Environmental Impact Assessment :
 Use the collected data to assess the environmental impact of air
pollution in a specific area and track the effectiveness of any implemented
pollution control measures.
9. Integration with IoT and Sensors :
 If possible, incorporate Internet of Things (IoT) devices and various
sensors to expand the system's functionality and gather additional environmental
data.
10.Educational Outreach :
 Consider the educational aspect of the project, making it a valuable
tool for teaching and raising awareness about air quality and its importance.
COMPONENTS REQUIRED :
 1. Arduino (e.g., Arduino Uno or Arduino Nano)
 2. Air quality sensors (e.g., MQ-135 for gases, SDS011 for particulate matter)
 3. Breadboard and jumper wires
 4. OLED display (optional)
 5. Computer with internet access for Tinkercad
PROCEDURE :
1. Log in to Tinkercad.
2. Click "Create new circuit."
3. Drag and drop the components onto the virtual breadboard.
 Place an Arduino board.
 Add your air quality sensor(s).
 If using an OLED display, add it as well.
4. Connect the components with jumper wires.
 Connect the sensor's signal pins to appropriate Arduino pins.
 Connect the power (VCC and GND) pins of the sensor(s) to the Arduino's 5V
and GND, respectively.
5. Write Arduino code to read data from the air quality sensors and display it on the
OLED screen (if using one).
6. Include code for sensor calibration and data conversion.
7. Make sure to include any libraries required for your components (e.g., Adafruit
SSD1306 for OLED displays).
8. Upload the code to your virtual Arduino in Tinkercad .
9. Click the "Start Simulation" button in Tinkercad to run the simulation.
10. Observe the virtual components' behavior and data readings in the simulation.
PROGRAM :
/*
Air Monitoring System
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////
The project's objective is to design a simple system that is used for simulating an Air
Monitoring System using Arduino Uno Board, Gas Sensor, Buzzer, LCD display, LEDs.
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////
This sketch is used for Air-Monitoring.
The LCD prints "Harmful Gas is Detected", the Buzzer will generate an alarm sound,
and the RED LED will be turned on when the Gas Sensor detects a harmful gas in its
reading range.
The Buzzer will be turned off and the GREEN LED will be turned on when the Gas
Sensor does not detect any harmful gases in its reading range.
 The Circuit Connections:
-LCD:
* LCD RS pin to digital pin 12
* LCD Enable pin to digital pin 11
* LCD D4 pin to digital pin 5
* LCD D5 pin to digital pin 4
* LCD D6 pin to digital pin 3
* LCD D7 pin to digital pin 2
* LCD R/W pin to ground
* LCD VSS pin to ground
* LCD VCC pin to 5V
* wiper to LCD VO pin (pin 3)
-Gas Sensor:
* Gas Sensor Analog read pin to analog pin A0
-Buzzer:
* Buzzer pin to digital pin 8
-LEDs:
* Green LED pin to digital pin 6
* Red LED pin to digital pin 7
*/
// include the library code:
#include <LiquidCrystal.h>
// initialize the library with the numbers of the interface pins
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);
int sensor = A0;
int val = 0;
int limit = 40;
void setup() {
 Serial.begin(9600);
 // declaring LEDs pins as OUTPUTS Pins and turned them off at the beginning.
 pinMode(7, OUTPUT);
 pinMode(6, OUTPUT);
 digitalWrite(6, LOW);
 digitalWrite(7, LOW);
 // set up the LCD's number of columns and rows:
 lcd.begin(16, 2);
 // Print a message to the LCD.
 lcd.print("Air Monitoring");
 lcd.setCursor(0, 1);
 lcd.print("System");
 delay(500);
 lcd.clear();
}
void loop() {

 val = analogRead(sensor); // Initialize the value of (val) Variable with the Gas
Sensor Reading.
 val = map(val, 306, 750, 0, 100); //Mapping the output voltage values from the Gas
Sensor to values in the range from 0 to 100.
 Serial.println(val); //Printing the Gas Sensor Reading in the Serial Monitor.
//If a harmful gas is detected.
 if (val > limit) {
 lcd.setCursor(0, 0);
 lcd.print("Harmful Gas is"); //Print a message to the LCD.
 lcd.setCursor(0, 1);
 lcd.print("Detected");
 digitalWrite(7, HIGH); //The Red LED wil be turned ON.
 digitalWrite(6, LOW); //The Green LED wil be turned OFF.
 tone(8, 1000); //The Buzzer will generate an alarm tone.
 delay(100); //Sound ON for 100 msec.
 noTone(8);
 delay(100); //Sound OFF for 100 msec.
 }

 else {
 lcd.clear(); //Clear the warning message from the LCD.
 noTone(8); //Sound OFF.
 digitalWrite(7, LOW); //The Red LED wil be turned OFF.
 digitalWrite(6, HIGH); //The Green LED wil be turned ON}}.

 
     
        
