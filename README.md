# Eau Claire's Salon

### This is a basic webpage to keep stylist and their clients in one organized place.

## By Maxwell Alvord


## Technologies Used 

* C#
* .Net 5.0
* HTML
* EntityFrameWork
* MySQL WorkBench

## Description 
This webpage will allow the user to add stylists to the data base. After the user may add clients and link them to their corresponding stylist. On the page that lists clients you can see their corresponding stylist in a list. The user may also see the list of stylist at anytime.


## Setup/Installation Requirements 

* Clone this repo: <https://github.com/maxwellalvord/Salon.Solution>
* cd into HairSalon.Solution
* Create an appsetting.json file at the root directory
* Open the appsetting.json file and enter:
```
{ 
  "ConnectionStrings": { 
    "DefaultConnection": "Server=localhost;Port=3306;database=[Database-Name];uid=root;pwd=[YOUR-PASSWORD];" 
  } 
}
```

* Download MySQL WorkBench
* Open MySQL WorkBench and In the Navigator > Administration window, select Data Import/Restore
* In Import Options select Import from Self-Contained File
* You will use .sql file type that is located the root directory HairSalon.Solution
* Navigate to the tab called Import Progress and click Start Import at the bottom right corner of the window.
* After you are finished with the above steps, reopen the Navigator > Schemas tab. Right click and select Refresh All.
* run dotnet restore and dotnet build from the HairSalon directory
* run dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0
* run dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2
* run dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0
* To interact with the local host website navigate to the HairSalon directory and run dotnet run
* click on  <http://localhost:5000>

## Known Bugs 

* Unable to list clients in stylist details

## License
[MIT](https://opensource.org/osd)

Copyright &copy;
2022 Maxwell Alvord

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<br>

## Contact Information
Contact me with questions and bugs at: <br>
[A link to my issues page on GitHub](https://github.com/maxwellalvord/maxwellalvord/issues)<br>
or email me at <a href = "mailto:maxwellalvord@gmail.com">maxwellalvord@gmail.com</a>