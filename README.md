# itis-6177-assignment14

Using sandman2, run the following command from this directory:

`sandman2ctl -p 5001 -l 'python+sqlite:///db.sqlite3'`

Using cURL:

1. All Users: `curl http://localhost:5001/users`
2. Single User: `curl http://localhost:5001/users/1`
3. Create User: `curl -X POST -d '{"username": "jjjschmidt", "fname": "John J", "lname": "Jingleheimerschmidt"}'`
4. Delete User: `curl -X DELETE http://localhost:5001/users/2`
