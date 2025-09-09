Django CS Robots

A simple, database-free Django app to manage your robots.txt file directly from the admin interface.

This package provides a straightforward solution for allowing site administrators to edit the robots.txt file without developer intervention. Instead of storing the content in a database model, this app reads from and writes directly to a physical file on your server. The file's path is fully configurable in your project's settings.py.

Key Features

    Edit in the Admin: Provides a simple and intuitive form within the Django admin to modify your robots.txt content.

    Database-Free: Directly reads from and writes to a file on the filesystem, avoiding database overhead and migrations.

    Configurable Path: You can specify the exact location of your robots.txt file in your settings.py for full control.

    Dynamic Serving: Includes a view that serves the robots.txt file dynamically, ensuring that any changes made in the admin are live immediately.

    Easy Integration: Designed to be a plug-and-play addition to any Django project.
