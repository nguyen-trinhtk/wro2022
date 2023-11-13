<h1>World Robot Olympiad 2022 - Team <i>VietRobot12</i></h1>
<h2>1. Overview</h2>
<h3>  a. The competition </h3>
<p>The World Robot Olympiad is a well-known annual international competition for young robotics enthusiasts, attracting more than 28,000 teams from more than 85 countries. This competition uses Lego Mindstorms and SPIKE, manufactured by LEGO Education.</p>
<h3>  b. Our team </h3>
<p>Our team, VietRobot 12, consists of 3 members: me (Nguyen), Khang, and Bao. I served as a programmer for the team. We participated in the B3 (Senior) Division of RoboMission. </p>
<h2>2. Rules</h2>
<h3>  a. Senior rules</h3>
<p>The theme for the 2022 WRO season is 'My Robot My Friend'. For the Senior Division, we had to assemble <i>The Care Robot</i> that can transport laundry and water bottles to appropriate areas and play balls with the patients while avoiding collisions with nurses and visitors on site. Additionally, each traditional run round (first day) will include a surprise extra point, and there will be a robot challenge (completely new rules) on the second day of the competition. For more information, please view <a href="https://wro-association.org/wp-content/uploads/WRO-2022-RoboMission-Senior.pdf">Senior Rules</a></p>
<h3>  b. Game field</h3>
<p> Here is a picture of our game field: [image](https://github.com/nguyen-trinhtk/wro2022/assets/125171883/932e5a41-c688-4c4d-8131-5a61e9848fc6)
</p>
<h2>2. Mechanics and algorithms</h2>
<h3>  a. Mechanics explanation </h3>
<p>Since each robot can use at most four motors, we decided to use two motors for locomotion; one more for the front crane that grabs water bottles, balls, and laundry blocks; and one for controlling the back door to drop bottles and laundry. Additionally, we've designed a slide to transfer grabbed objects from the robot's front to its back. The front crane also has two modes: hold (grabbing without levitating) and collect (grabbing while levitating the block to the slide). </p>
<p>For a better understanding of our design, see our <a href="https://github.com/nguyen-trinhtk/wro2022/blob/main/detached-model.io">3D Design file</a>.</p>
<h3>  b. Algorithms explanation </h3>
<p>Our chosen path for the robot is depicted in the following picture: </p>
![image](https://github.com/nguyen-trinhtk/wro2022/assets/125171883/5a9f2005-1428-4cd5-b8c2-82e174627bc8)
<p>Sample run video: </p>

https://github.com/nguyen-trinhtk/wro2022/assets/125171883/8079cbbb-647d-42bf-8de3-8fd9d3eb6fc4


<p>In this repository, I have included different code versions for this robot, divided into two periods: May-August (National Round preparation) and August-November (International Round prep). Since it is difficult to stabilize its performance, we have made a lot of improvements.</p>
<p>The final version can be found here: <a href="https://github.com/nguyen-trinhtk/wro2022/blob/main/runWRO.ev3">International Final Coded</a></p>
<h2>3. Results</h2>
<h3>  a. National round</h3>
<p>In the national competition, which took place in Ho Chi Minh City, our team placed second, therefore advancing to the international final as one of Vietnam's representatives in the senior division. </p>
<h3>  b. International final</h3>
<p>In the international final in Dortmund, Germany, we placed 23rd overall. According to our cumulative score, we received a bronze award. The experience was worthwhile because we had a chance to learn from other teams and had many cultural exchanges.</p>
