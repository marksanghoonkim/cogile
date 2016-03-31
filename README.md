# nimblecode

Nimblecode was created by four software engineers at Makersquare, an immersive software engineering program in Los Angeles, CA. Are you looking to hire? Check out our Github pages.

## Getting Started

Here is a quick step by step to get started with our project


### Prerequisities

Fork the repo and clone locally

#### You must node installed and have a MySQL db to connect to
The config file to connect to db is in server->db->config->config.js

#####Example of config layout:
```
module.exports = {
    db_host: '52.53.212.182',
    db_user: 'remote',
    db_password: 'hello321',
    db_name: 'nimble_code_db',
    charset: 'utf8',
    secret: 'nimble_code_secret',
    clientID: '5650911cf15eb84602a8',
    clientSecret: 'e41b6c3c03214af93621c7f7d280c1cf5b2f9fe6',
    callbackURL: 'http://127.0.0.1:8080/api/oauth/github/callback'
  };


```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* Dropwizard - Bla bla bla
* Maven - Maybe
* Atom - ergaerga

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
