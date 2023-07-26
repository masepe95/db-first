# DB AUTODEALER

| Column               | Type        | Attributes                    |
| -------------------- | ----------- | ----------------------------- |
| id                   | BIGINT      | PRIMARY-KEY<br>AUTO-INCREMENT |
| brand                | varchar(20) | NOT NULL                      |
| model                | varchar(50) | NOT NULL                      |
| engine               | varchar(20) | NOT NULL                      |
| immatricolation_year | YEAR        | NOT NULL                      |
| kms                  | mediumint   | NULL                          |
| license_plate        | varchar(7)  | NULL                          |
| cost                 | mediumint   | NULL                          |
| price                | mediumint   | NULL                          |
| color                | varchar(30) | NULL                          |
| description          | text        | NULL                          |
| location             | varchar     | NULL                          |
| pictures             | varchar     | NULL                          |
| previuous-owners     | tinyint     | NULL                          |
