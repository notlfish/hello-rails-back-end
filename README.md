# hello-rails-back-end

Backend for an example web app that displays greetings stored in a database.

## Built With

- Ruby on Rails

## Getting Started
**You'll need to have git and npm installed in you environment to follow these instructions.**
To get a local copy of the repository please run the following commands on your terminal:

```bash
$ cd <folder>
$ git clone https://github.com/notlfish/hello-rails-back-end.git
$ cd hello-rails-back-end
```

To be able to serve the project on your computer, you'll need to install the developer's dependencies.
```bash
$ bundle install
```

With this, you can use
```bash
$ rails db:setup
$ rails s -p 3000
```
to boot the rails app.

## API Endpoints
GET /v1/greeting

Headers: {
    'Content-Type': 'application/json'
}

Response: json : {
    'greeting': <randomly chosen greeting from database>
}

## Author

👤 **Lucas Ferrari Soto**

- GitHub: [@notlfish](https://github.com/notlfish)
- Twitter: [@LucasFerrariSo1](https://twitter.com/LucasFerrariSo1)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/lucas-mauricio-ferrari-soto-472a3515a/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/JAAR91/Awesome-books/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

[MIT](/LICENSE)
