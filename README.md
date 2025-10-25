# CS-340
Writing Maintainable, Readable, and Adaptable Programs

To write programs that are maintainable, readable, and adaptable, I focus on clear structure, modular design, and consistent documentation. In Project One, I built a CRUD Python module that handled all database interactions for the Austin Animal Center dataset. This approach separated the data access logic from the dashboard code, which made my work in Project Two much easier. Instead of rewriting queries inside the dashboard, I simply imported the CRUD class and called its methods.
The advantages of working in this way were significant:

•	Maintainability: If database credentials or structures change, I only need to update the CRUD module instead of searching through the entire dashboard code.

•	Readability: The CRUD methods (create, read, update, delete) are self-explanatory, so anyone reading the code can quickly understand their purpose.

•	Adaptability: The same CRUD module can be reused for different projects or extended to handle more advanced queries in the future.

In fact, I could use this module again in future dashboards or applications that require working with animal shelter data or similar collections. By changing only the database and collection parameters, the CRUD class could be applied to other organizations with very little modification.

Approaching Problems as a Computer Scientist

When approaching problems as a computer scientist, I start by breaking down client requirements into smaller technical tasks. For Grazioso Salvare, this meant first identifying the functional requirements:

•	Retrieve animal outcome data from MongoDB

•	Display the data in a dynamic, filterable table

•	Show visualizations such as a geolocation map and bar chart

Compared to earlier courses, this project required me to think in terms of both back-end (data retrieval) and front-end (visualization and user interaction) at the same time. I didn’t just write code to solve a math problem or complete a single function—I designed a system that connected a database, a user interface, and visual elements in a cohesive way.
For future database projects, I would continue using strategies such as:

•	Modularization: separating the database logic (CRUD) from the interface logic (dashboard).

•	Prototyping: starting with small test queries and simple widgets before building the full interactive system.

•	Scalability: designing queries and dashboards that can handle larger datasets without breaking or slowing down.

What Computer Scientists Do and Why It Matters

Computer scientists create tools, systems, and applications that allow organizations to make better use of their data, automate processes, and serve their customers more effectively. In this project, my work directly supported Grazioso Salvare’s mission by enabling them to filter and visualize animal outcome data.
With this dashboard, Grazioso Salvare can:

•	Quickly analyze trends in animal rescues (such as water or wilderness rescues).

•	Visualize geographic data to better allocate resources where they are needed.

•	Present findings in a way that is both professional and actionable for decision-makers.

This kind of work matters because data without context is difficult to act on. By designing an interactive dashboard, I translated raw data into insights that can guide real-world rescue efforts. For a company like Grazioso Salvare, that means they can save more animals, train their teams more effectively, and communicate their impact more clearly to partners and donors.

