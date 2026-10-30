#EXP-2
#DATE: 30\10\2026
#NAME: MEIYAPPAN S
#REF.NO: 212225080029
# Exploration-of-AI-Use-Case-Case-study-on-self-driving-cars
# AIM
To study the application of Artificial Intelligence (AI) in self-driving cars and understand how AI technologies help vehicles perceive their surroundings, make decisions, and navigate safely without continuous human control.
# THEORY
Self-driving cars work by using intelligence to copy human driving skills and go beyond them without any help from a person behind the wheel. The main idea is a loop of sensing, thinking and acting. Sensors such as cameras, LiDAR and radar collect information about the surroundings. Artificial intelligence models like CNNs process this data to recognize roads other vehicles and people walking. The system then tries to guess what other objects might do next. It uses decision-making algorithms to figure out the way to move forward. This plan is turned into actions—like turning the steering wheel pressing the brake or speeding up—and carried out by the car’s own control systems. At the end of the day the theory is, about mixing perception, prediction and control all in time. This allows the car to navigate safely and independently.
# WORKING
Self-driving cars depend on a system that combines intelligence and hardware working as one:

**a) Sensing (Perception Layer)**
- Cameras – take pictures of the world around the car (lane lines, traffic signs people walking).
- LiDAR (Light Detection and Ranging) – sends out laser beams to create a detailed 3D picture of the area around the car.
- Radar – finds how far away and how fast objects are moving and works well even in bad weather.
- Ultrasonic sensors – check for things close by when parking or avoiding obstacles.
- GPS/IMU – helps the car know where it is and which way it is facing.

**b) Perception (AI Interpretation)**
- CNNs look at the pictures from cameras and figure out what they see: people, cars stop signs, road signs.
- Algorithms bring together data from LiDAR, radar and cameras to get a full picture of the world around the car (fixing each sensors mistakes).

**c) Localization & Mapping**
- The car checks the information it gets from sensors against high-definition maps to know where it is on the road right down to the centimeter.

**d) Prediction**
- Computer models try to guess what will happen next, with other cars and people nearby (like "will that person step into the road?" or "will that car move over?").

**e) Path Planning & Decision-Making**
- Programs figure out the best way to drive making sure it is safe and efficient while following traffic rules and avoiding things in the way.

**f) Control**
- The final decision is turned into actions. Like changing the direction of the wheels speeding up or stopping. And sent to the parts of the car that make it move.

Sensors → Perception (CNNs) → Sensor Fusion → Localization → Prediction → Planning → Control → Vehicle Action

<img width="620" height="396" alt="image" src="https://github.com/user-attachments/assets/063e6c72-23c4-460b-925e-f06760beec83" />

# Benefits
- Reduced accidents – over 90% of road accidents are linked to human error (fatigue, distraction, intoxication); AI doesn't get tired or distracted
- Increased mobility – enables independent travel for the elderly, disabled, or those unable to drive
- Traffic efficiency – optimized routing and coordinated driving can reduce congestion and fuel consumption
- Lower emissions – smoother acceleration/braking patterns and integration with electric vehicles reduce environmental impact
- Productivity gains – passengers can work, rest, or engage in other activities during travel
- Cost savings – potential reduction in insurance costs, fewer accident-related expenses, optimized fleet logistics for businesses
- 24/7 availability – autonomous taxis/delivery vehicles can operate without driver shift limitations
# List of Ethical Issues
**1. The Trolley Problem / Moral Decision-Making**
- In a situation where an accident cannot be avoided how should the car decide who to protect. The person inside the car a person outside the car or the person who will suffer the harm? Who is responsible for programming this type of logic?

**2. Data Privacy**
- Self-driving cars constantly gather information about where they go how they drive and even what happens inside the car through cameras, which creates worries about being watched and having that information used in the way.

**3. Job Displacement**
- If self-driving cars become common many jobs for people who drive taxis, trucks and delivery vehicles could disappear. This would affect a lot of workers.

**4. Algorithmic Bias**
- Some research has found that object-detection systems do not always work well for people with darker skin tones, which brings up questions, about fairness and safety.

**5. Cybersecurity Risks**
-Self-driving cars can be hacked; if a car is taken over by someone who should not have control it could be used to hurt people or cause accidents.
# RESULT
Self‑driving cars have shown that AI can carry out driving tasks with a level of precision that often surpasses human capability when conditions are controlled. Experiments by companies such as Waymo and Tesla have displayed accident rates in chosen settings along with smoother traffic flow and better fuel savings. Yet the findings also expose problems: sensors fail in bad weather AI sometimes misjudges unpredictable events and a handful of high‑profile crashes have sparked safety worries. These results underline that although the technology is moving fast it is still not fully dependable, for unsupervised use. In short the evidence points to a bright but still developing field that needs trials, rules and adjustments before it can be widely adopted in a truly autonomous mode
