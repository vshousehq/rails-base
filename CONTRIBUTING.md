# System dependencies

Install the dependencies managed by [Brewfile](/Brewfile) using:

```shell
brew bundle
```

Install ASDF plugins:

```shell
asdf plugin add ruby https://github.com/asdf-vm/asdf-ruby.git
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
asdf plugin-add postgres
```

# Setup

# Packages

```shell
bundle install
yarn install
```

## Database

```shell
rake db:setup
rake db:migrate
```


# Testing suite


```shell
rspec
```

# Running the application

```shell
bin/dev
```

# Deployment

App is automatically deployed to [https://vshouse-checklists.herokuapp.com/](https://vshouse-checklists.herokuapp.com/) in heroku when
merged to `main` branch.
