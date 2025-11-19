<p align="center">
    <h2>   Create Laravel google authentication </h2> 

</p>

<p>
## About project
This Laravel sipmle project to create user signing using his google acount , follow steps : 
</p>

- download project on your local.
- update composer use command : composer update
- change file 'env-examle' to 'env'.
- create database and cofig in your env file.
- create generation key.
- put GOOGLE_CLIENT_ID, GOOGLE_CLIENT_SECRET and GOOGLE_REDIRECT_URL in your .env such as : 
    - GOOGLE_CLIENT_ID=your-client-id
    - GOOGLE_CLIENT_SECRET=your-client-secret
    - GOOGLE_REDIRECT_URL=http://your-domain.com/auth/google/callback
- migrate databse.
- load your project 'php arisan serve'
- open browser ans routing this 'http://127.0.0.1:8000/login'
