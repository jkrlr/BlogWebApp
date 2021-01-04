# Educational Blogs

A simple webapp for writing blogs for educational and learning purposes using django web framework.

## Technology Stack

**Frontend:** HTML, CSS, JavaScript  
**Backend:** Python/Django  
**Database:** SQL (SQLite3)  

And additional requirements are in [**requirements.txt**](https://github.com/jkrlr/BlogWebApp/blob/master/BloggingApp/mysite/requirement.txt)

## Contributing

### Setting-up the project

  * Download and install Python 3.8
  * Download and install Git.
  * Fork the Repository.
  * Clone the repository to your local machine `$ git clone https://github.com/<your-github-username>/BlogWebApp.git`
  * Change directory to BlogWebApp `$ cd BlogWebApp`
  * Install virtualenv `$ pip3 install virtualenv`
  * Create a virtual environment `$ virtualenv env -p python3.8`  
  * Activate the env: `$ source env/bin/activate` (for linux) `> ./env/Scripts/activate` (for Windows PowerShell)
  * Install the requirements: `$ pip install -r requirements.txt`
  * Make migrations `$ python manage.py makemigrations`
  * Migrate the changes to the database `$ python manage.py migrate`
  * Create admin `$ python manage.py createsuperuser`
  * Run the server `$ python manage.py runserver`
 

### Contributing Guidelines 
  * Feel free to open an issue to report a bug or request a new feature.
  * Before starting to work on an issue, comment on that issue that you want to work on this and then only start to code.
  * Create a new branch with a related name of the motive i.e. bug/refactor/feature and commit your changes in that branch only.  
  * Send a pull request anytime :) 
