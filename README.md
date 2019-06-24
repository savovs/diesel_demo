# Diesel.rs + Docker 

Before starting, run the database:
`docker-compose up -d`


Write a post:
`cargo run --bin write_post`

Show all posts:
`cargo run --bin show_posts`

Publish a post by id: 
`cargo run --bin publish_post 1`

Delete a post by title:
`cargo run --bin delete_post demo`



Guides: 
http://diesel.rs
https://docs.docker.com/compose/overview/