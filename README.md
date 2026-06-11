cd ..
echo "# Task Manager - ASP.NET Core" > README.md
echo "" >> README.md
echo "A task management web application built with ASP.NET Core MVC, C#, Entity Framework Core, and SQL Server." >> README.md
echo "" >> README.md
echo "## Features" >> README.md
echo "- User Registration & Login (ASP.NET Core Identity)" >> README.md
echo "- Create, Edit, Delete Tasks" >> README.md
echo "- Task Priority (Low / Medium / High)" >> README.md
echo "- Task Status (Pending / In Progress / Completed)" >> README.md
echo "- Due Date tracking" >> README.md
echo "" >> README.md
echo "## Tech Stack" >> README.md
echo "ASP.NET Core MVC | C# | Entity Framework Core | SQL Server | Bootstrap 5" >> README.md
cd TaskManager
git add .
git commit -m "Add README"
git push
