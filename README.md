# golang-crud-mysql
Golang simple CRUD with MySQL

### Step 1: Prepare and Import MySQL driver into your project
````
go get -u github.com/go-sql-driver/mysql
````

### Step 2: Creating Database and the Employee Table
````
DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
````

### Step 3: Creating Struct, Handler and Handler Function
Let's create a file named main.go and put the following code inside it.

### Step 4: Creating Template files
Now it's time to build the Template files of our CRUD application. Create form folder at same location where we have created main.go.

### Run the project
````
go run main.go
````
