Inventory - Starter Code
==================================

Learn how to save user's data in the app.

First you'll use Room to read and write changes to a database.

Then you'll use Preferences DataStore to store user preferences in the app.

https://developer.android.com/courses/pathways/android-basics-kotlin-unit-5-pathway-2

Introduction
------------

This app is an stater code for an Inventory tracking app. Demos how to add, update, sell, and delete
items from the local database.
This app demonstrated
the use of Android Jetpack component [Room](https://developer.android.com/training/data-storage/room) database.



Summary
--------------

- Define your tables as data classes annotated with @Entity. Define properties annotated with @ColumnInfo as columns in the tables.
- Define a data access object (DAO) as an interface annotated with @Dao. The DAO maps Kotlin functions to database queries.
- Use annotations to define @Insert, @Delete, and @Update functions.
- Use the @Query annotation with an SQLite query string as a parameter for any other queries.
- Use Database Inspector to view the data saved in the Android SQLite database.
