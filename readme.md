
Author: Ayinde Oluseyi P
Profession: Software Engineer


BLOG RESFUL API USING LARAVEL FRAMEWORK

The BLOG API has the following end points:

AUthentication And Authorization

http://127.0.0.1:8000/api/blog/register

http://127.0.0.1:8000/api/blog/login



Articles


http://127.0.0.1:8000/api/articles 


http://127.0.0.1:8000/api/articles      


http://127.0.0.1:8000/api/articles/id


http://127.0.0.1:8000/api/articles/save    (Auth required)


http://127.0.0.1:8000/api/articles/update   (Auth required)


http://127.0.0.1:8000/api/articles/delete   (Auth required)


INSTALLATION

Clone the repo by running 

git clone https://github.com/rogong/blogRESFULAPI.git

Composer Update 

To view it in browser 

run "php artisan serve"




Post Examples

<prev>
    
    Using Form-Date in Postman

Key                         Value 

name                      your name
email                     your email
password                  your name
password_confirmation      confirm password   (min 6 chars)
    
    </prev>

When the article is saved 

{
    "status": "success",
    "status_code": 201,
    "message": "Article created successfully!",
    "data": {
        "id": 1,
        "title": "Blog title",
        "slug": "Blog title",
        "excerpts": "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem necessitatibus nemo reiciendis impedit, quae sunt saepe, autem, odit mollitia laudantium ullam iste dicta sapiente magni facere. Ratione impedit sed dolore?",
        "body": "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem necessitatibus nemo reiciendis impedit, quae sunt saepe, autem, odit mollitia laudantium ullam iste dicta sapiente magni facere. Ratione impedit sed dolore?",
        "user": {
            "id": 1,
            "fullname": "Ayinde Oluseyi",
            "email": "p.oluseyi@yahoo.com"
        }
    }
}

etc.






