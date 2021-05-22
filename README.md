# _Eau Claire's Salon_

#### _An app to keep track of a salon's stylists and clients_

#### By _Thomas Russell_

## Technologies Used

- _C#_
- _ASP.NET Core_
- _Razor_
- _MySQL_
- _MySQLWorkbench_
- _EF Core_
- _CSS_
- _Bootstrap_
- _Markdown_

## Description

_This is a C#/ASP.NET Core application that allows a salon owner named Claire to keep track of all of her salon's stylists and their clients. This application uses Entity to communicate with with a MySQL database hosted by MySQL Workbench. The application allows the user to add, edit, delete, and view the details of both stylists and their clients._

## Setup and Use

### Prerequisites

- [.NET 5 SDK](https://dotnet.microsoft.com/download/dotnet/5.0)
- A text editor like [VS Code](https://code.visualstudio.com/)
- A browser like Chrome or Firefox
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

### Installation

1. Clone the repository: `$ git clone https://github.com/tprussell19/HairSalon.Solution`
2. Navigate to the `HairSalon.Solution/` directory on your computer
3. Open with your preferred text editor to view the code base
4. Create a database using SQL via MySQL:
   To import the database structure:
   - Open MySQL Workbench
   - Select the MySQL instance in the **MySQL Connections** section. If prompted, enter your password.
   - Click on the **Adminstration** tab
   - Click on _Data Import/Restore_
   - In the Data Import window that appears, select _Import from Self-Contained File_
   - Navigate the file selection to your cloned project location and choose the `.sql` file at `HairSalon.Solution/thomas_russell.sql`
   - At the **Default Target Schema** option, choose _New..._ and name the schema `thomas_russell`
   - Click the _Start Import_ button at the bottom-right; if you can't find it, you may need to maximize your MySQL Workbench window
   - Once the import is complete, navigate to the **Schemas** tab to find the imported schema. If it does not show up right away, click the refresh button just underneath the **Schemas** tab
5. To run the app:
   - Navigate to `HairSalon.Solution/HairSalon` in your command line
   - Run the command `dotnet restore` to restore the dependencies that are listed in the .csproj
   - Run the commmand `dotnet build` to build the project and its dependencies into a set of binaries
   - Finally, run the command `dotnet run` to run the project!
   - Note: `dotnet run` also restores and builds the project, so you can use this single command to start the app and launch
   - If the application does not automatically launch in your browser, you will need to open a browser window and navigate to "localhost:5000"

## Known Bugs

- _No known bugs_

## License

_MIT © Thomas Russell 2021_

## Contact Information

Thomas Russell _t.p.russell19@gmail.com_
