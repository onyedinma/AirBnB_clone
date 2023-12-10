## AirBnB Console App: Managing Data for Your Platform

This document introduces the AirBnB console application, a tool designed to manage data essential to a platform, similar to an Airbnb platform. It details the app's functionalities and provides usage instructions.

**What is AirBnB?**

AirBnB is a project focused on building a platform management console. This **console** provides a command-line interface for interacting with data related to users, places, amenities, cities, and reviews.

**AirBnB Console Features:**

* **Create objects:** Generate new instances of various classes like User, Place, Amenity, City, etc.
* **Show objects:** View specific object details by providing its ID.
* **List all objects:** Get a list of all instances of a particular class.
* **Update objects:** Modify existing object attributes.
* **Destroy objects:** Permanently delete objects.
* **Command interpreter:** Interact with the system through a user-friendly interface.
* **Data storage:** Store data persistently in a JSON file.
* **Unit tests:** Ensure functionality with comprehensive test cases.

**Getting Started:**

1. Clone the AirBnB repository: `git clone https://github.com/onyedinma/AirBnB_clone.git`  (Note: Replace AirBnB_clone with the actual AirBnB repository name)
2. Open the `/AirBnB` directory.
3. Ensure Python 3.4.3 or later is installed.
4. Run `console.py` to launch the application.

**Using the Console:**

Here's a table summarizing the available commands:

| Command | Description | Usage |
|---|---|---|
| **help** | Show available commands. | `help` |
| **quit** | Exit the console. | `quit` |
| **create** | Create a new object instance. | `create` `<class>` |
| **show** | View object details. | `show` `<class>` `<id>` |
| **destroy** | Delete an object instance. | `destroy` `<class>` `<id>` |
| **all** | List all instances of a class. | `all` `<class>` |
| **update** | Modify existing object attributes. | `update` `<class>` `<id>` `<key>` `<value>` |

**Further Information:**

* **Command Descriptions:**
    * **help:** Displays available commands and their descriptions.
    * **quit:** Exits the console application.
    * **create:** Creates a new instance of a specified class.
    * **show:** Displays details of a specific object identified by its class and ID.
    * **destroy:** Deletes an object identified by its class and ID.
    * **all:** Lists all instances of a specified class.
    * **update:** Modifies an object's attributes using its class, ID, key, and value.
* **Additional Resources:**
    * The README.md file provides further details about the project.
    * The project repository contains the source code and unit tests.
    * For assistance, consider contributing to the project by reporting bugs, suggesting features, or creating pull requests.

**Examples:**

* **Help:** Enter `help` followed by the desired command to learn its usage. For example, `help create`.
* **Create User:** Use `create User` to generate a new user.
* **Show User:** Use `show User <id>` to view details of a specific user.
* **Destroy User:** Use `destroy User <id>` to permanently remove a user.
* **List all Users:** Use `all User` to see all existing user instances.
* **Update User:** Use `update User <id> <key> <value>` to modify a user's attributes.

**Project Scope:**

The initial phase of the AirBnB project focuses on building the console and connecting it to a JSON storage system for data persistence. This enables saving and retrieving information.

**Additional Notes:**

* The AirBnB console app is under active development.
* Contributions are welcome in the form of bug reports, feature suggestions, and pull requests.

**Feel free to explore the console and its functionalities to gain a deeper understanding of how it manages data for your platform.**
