# Task Management

## ERD
![](https://i.imgur.com/Gr8X0vA.png)


## Table Schema

* Users

| column    | datatype |
| --------- | -------- |
| id        | int      |
| create_at | datetime |
| update_at | datetime |
| name      | string   |
| password  | string   |
| email     | string   |


* Tasks

| column      | datatype |
| ----------- | -------- |
| id          | int      |
| create_at   | datetime |
| update_at   | datetime |
| title       | string   |
| description | text     |
| start_at    | datetime |
| end_at      | datetime |
| user_id     | int      |
| order       | int      |
| status      | int      |

* Tags
 
| column    | datatype |
| --------- | -------- |
| id        | int      |
| create_at | datetime |
| update_at | datetime |
| name      | string   |

* Taggings

| column    | datatype |
| --------- | -------- |
| id        | int      |
| create_at | datetime |
| update_at | datetime |
| task_id   | int      |
| tag_id    | int      |

