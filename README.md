 👋 Hi, I’m @gaylaht
- 👀 I’m interested in data analytics and game development.
- 🌱 I’m currently learning C++ and sharpening my C# skills after learning SQL and Python.
- 💞️ I’m looking to collaborate on health care projects and any data deep dives
- 📫 How to reach me heygaylah@gmail.com
- ⚡ Fun fact: my middle name is spelled wrong on my birth certificate and I was the one to tell my parents.

<section class="Data Projects"> 
    <h1>Energy Consumption and Spending in the South, 2020</h1>
    <p class="project-subtitle">How to Advise Energy Consumers</p>
    <div class="project-meta">
        <span>Tools: Excel, PowerBI</span>
        <span>Duration: 1 week</span>
    </div>
</section>


<section class="project-context">
    <h2>Background</h2>
    <p>Energy stakeholders and consumers would like to know the
        current state of energy consumption and what could be points of growth for energy efficiency.
        The key questiosn to ask:
        Are older homes better or worse for energy conservation?
        Does income impact how much spending a household uses or their consumption?
        What is the housing type with the smallest amount of consumption?
        The federal government has passed legislation to help electrify the country. What is the most used energy source in the South?
  
</section>


<section class="project-approach">
    <h2>Data Structure</h2>
    <ul>
        <li>Data was cleaned for blank values, inconsistent values, and correct formatting in Excel</li>
        <li>This data is provided by the United States Energy Information Administration. This survey is done in 4 year increments. This data visualization seeks to understand the inquiries of:
  <i>Are older homes better or worse for energy conservation?
  Does income impact how much spending a household uses or their consumption?
  What is the housing type with the smallest amount of consumption?
  The federal government has passed legislation to help electrify the country. What is the most used energy source in the South?</i>></li>
    </ul>
</section>

		
<section class="project-results">
    <h2>Results & Business Impact</h2>
    <p>
        The data shows that spending fluctuated significantly between older homes of 1950 to more current homes. Spending in houses constructed between 2016-2020 marked the lowest in over half a century.
The highest earners in the South consume almost 6 times the energy of the lowest earners.
Apartments make up the smallest percentage of spending and consumption. 
Electrification is well underway in the South with consumption almost parallel to gas energy. 

  
</section>




<section class="Data Projects"> 
    <h1>Analyzing A'ja Wilson, the 4 Time WNBA MVP</h1>
    <p class="project-subtitle">Analyzing her stats</p>
    <div class="project-meta">
        <span>Tools: Excel, MySQL</span>
        <span>2 days</span>
    </div>
</section>


<section class="project-context">
    <h2>Background</h2>
    <p> A'ja Wilson has now become the first and only woman in the WNBA to win the Most Valuable Player
        award 4 times. Team ownders would like a better insight to performance indicators that set her 
        apart from the rest of the league.
    </p>
</section>


<section class="project-approach">
    <h2>Data Structure and questions</h2>
    <ol>
        <li>Data collection was done from the official WNBA website. This data was collected from the 2025 regular seaosn. Data cleaning was done in MySQL</li>
        <li>How consistent and all around is A'ja Wilson?</li>
        <li>In the areas where she lacks defensively, does she make up for it offensively? </li>
        <li>Who are the players that slow down her momentum?  </li>
    </ol>
</section>


<section class="project-technical">
    <h2>Technical Implementation</h2>
    <pre><code>
        SELECT AVG(Blocks), AVG (points), AVG(Assists), AVG(Rebounds)
        FROM new_schema.thestats;

        SELECT MAX(Blocks)
        FROM new_schema.thestats;

        SELECT * 
        FROM new_schema.thestats
        WHERE (Blocks) > 2
        ORDER BY Points DESC;

        SELECT * 
        FROM new_schema.thestats
        WHERE (Blocks) < 2
        ORDER BY Points DESC;
        </code></pre>
</section>


<section class="project-results">
    <h2>Results & Business Impact</h2>
    <p>
        A'ja Wilson leads in stats both offensively and defensively. She is not a roleplayer
        (as indicated by her double digit statistics across the board). On nights where her points
        are not in the twenty point range, her assists count is high. This analysis focused heavily
        on Blocks due to A'ja being awarded co-defensive player of the year. She missed few games
        due to injury. When looking at the stat sheet and the games, the Seattle Storm, Indiana Fever,
        and Minnesota Lynx provide the biggest threat to her either offensivley or defensively. However, 
        she has more games where her blocks were above her average than zero. 
    </p>
</section>



<!---
gaylaht/gaylaht is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
