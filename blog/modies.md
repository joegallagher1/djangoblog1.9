modies.md

# im our blog

Features
================================
Blog will have the following features

1. post(table is database)
2. categories(table is database)
3. tag(table in database)
4. Author(table is our database)

Let us make a relation between our tables
========================================
1. Post can have many categories and a category can have many post (related between post and category)
2. Tag can have many posts amd a post can have nay tags
3. author can have many posts however an post can only have 1 author.

attributes for tables
=====================
Post
====
1. title
2. create_data
3. body
4.tags
5.categories
6.Author

Categories
============
1. cat_name
2 cat_discription

Author
========
1. Author_name
2. Author_email
3. author_bio

Tag
====
1. Tag_name
