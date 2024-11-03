### Samll Project using fetch-ap

We will fetch our data from a public api called 'random user generator api'
we will grap a username, a profile picture , an email address , phone
location and age

js```

    // we will make a get request to this endpoint
    - https://randomuser.me/api

    const url = 'https://randomuser.me/api';
    fetch(url)
    .then(response => console.log(response.json()))
    .catch(error => console.log(error))

```

```
