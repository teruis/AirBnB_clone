**README.md for AirBnB Clone Project**

**Project Description**

This project is a console-based clone of the AirBnB website. It allows users to create, manage, and search for AirBnB listings.

**Command Interpreter**

The command interpreter can be started by running the following command:

```
./console.py
```

Once the command interpreter is running, users can type in commands to interact with the application. For example, to create a new AirBnB listing, users would type the following command:

```
create listing
```

The command interpreter would then prompt the user for information about the listing, such as the title, description, and location. Once the user has entered all of the required information, the command interpreter would create a new listing and assign it a unique identifier.

To search for AirBnB listings, users would type the following command:

```
search listing <query>
```

The command interpreter would then display a list of all AirBnB listings that match the query.

**Getting Started**

To get started with this project, clone the following repository:

```
git clone https://github.com/Guillaume/AirBnB_clone
```

Once the repository has been cloned, navigate to the project directory and run the following command to install the required dependencies:

```
pip install -r requirements.txt
```

To start the command interpreter, run the following command:

```
./console.py
```

**Testing**

To run the unit tests for this project, run the following command:

```
python3 -m unittest discover tests
```