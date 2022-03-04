#### Project Setup


MONGO_URI

JWT_SECRET

#Access the API documentation here : https://job-api-shaurya.herokuapp.com/api-docs/

![Uploading image.png…]()


#Access the Frontend Application using the API in backend here :  https://frontend-jobs-shaurya.herokuapp.com/


After that run this command

```bash
npm install && npm start
```

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
