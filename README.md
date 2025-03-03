🕶️ Analyzing Green-Eyed Criminals!

Watching the Banshee TV series turned me into a detective! 🔥👀

I recently got hooked on a thrilling crime series called Banshee, and honestly, it gave me some serious cop vibes. 😎
The story revolves around a master criminal who steals a sheriff’s identity and dives into a city full of crime and chaos!
He’s both a cop and a criminal, with the mafia chasing him down. A pure adrenaline-fueled crime-action masterpiece!


🚔 My Detective-Inspired Data Project

After watching Banshee, I felt like solving a crime myself!
Imagine you only have one clue: Green Eyes 👀
You need to figure out what kind of criminal they are, their age, and even their hair color!

For this project, I had access to a criminal records database, but the only thing I knew was their green eyes.
So, I decided to analyze their characteristics! 🤔


🔎 Step 1: Filtering Data from SQLite

First, I used an SQL query to extract only the criminals with green eyes from the database:

SELECT *  
FROM superheros  
WHERE eye_color = 'Green Eyes';

Now, I have a focused dataset that only contains relevant individuals! ✅


🧹 Step 2: Data Cleaning and Organization

As usual, raw data isn't always clean.

Removed unnecessary columns

Dropped duplicates and missing values

Renamed columns for better readability (e.g., first_appearance → Birth_Year)


📊 Step 3: Criminal Data Visualization

🔥 Hair Color Analysis 👩‍🦰👨‍🦳

The first thing I analyzed was hair color.
Using value_counts() and Seaborn, I created a bar chart to visualize the number of criminals for each hair color.

📌 Results?

Most green-eyed criminals had red hair! 😲🔥
(A secret red-haired gang, perhaps? 🤔)

The next most common were black-haired individuals, followed by blondes.


🥧 Pie Chart for Hair Color Distribution
To make the comparison even clearer, I created a pie chart to show the percentage of each hair color among green-eyed criminals.
One quick look and you can tell—red-haired criminals dominate!


📆 Birth Year Analysis

Next, I analyzed criminals’ birth years.

Extracted birth years from Birth_Year

Used a line plot to visualize the distribution over time


📌 Findings?
Most green-eyed criminals were born between 1990 and 2000! 😲


🔍 Conclusion: Profiling Green-Eyed Criminals

✅ Most have red hair
✅ Most were born between 1990 and 2000

📊 So, if you ever have a police case with only one clue—green eyes 👀,
this data might just help you track them down! 🚔😂
