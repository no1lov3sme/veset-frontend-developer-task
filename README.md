![Veset](veset.svg)

Task for Veset Frontend Developer position.

## Description
You need to create a React app, that outputs a list of team members and allows to manage them (CRUD).

### Technologies
1. React
2. REST API
3. Any CSS framework

**You are allowed to use any other technologies to complete this task.**

### REST API
`GET https://60d1820c5b017400178f3bd5.mockapi.io/api/1/team-members`
> Outputs a list of team members

`POST https://60d1820c5b017400178f3bd5.mockapi.io/api/1/team-members`
> Creates a new team member

`PUT https://60d1820c5b017400178f3bd5.mockapi.io/api/1/team-members/{id}`
> Updates a team member


`DELETE https://60d1820c5b017400178f3bd5.mockapi.io/api/1/team-members/{id}`
> Deletes a team member

### Data model
```
{
  "id": "1",
  "firstName": "John",  
  "lastName": "Doe",
  "position": "Developer",
  "description": ""
}
```

All fields except `description` are mandatory.

### Additional tasks
Code coverage with tests, team members list filtering or any other improvement of initial requirements will be accounted as a plus but ___not required___.

### Terms
We expect to receive a github repository link with implemented task in 1 week from the day task is sent to candidate.
