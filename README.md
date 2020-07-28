# ASSOCIATIONS: PRIVATE EVENTS

In this Ruby on Rails project we are creating a website similar to Eventbrite. Users can create events and invite people to these events. A user can only see an event that they have been invited to. The creator of an event is automatically invited to that event.

# [LIVE LINK](https://private-events-lotr.herokuapp.com/)

# Authors

Marios Kanellopoulos
- Github: [@mariosknl](https://github.com/mariosknl)
- Twitter: [@mariosknl](https://twitter.com/MariosKnl)
- Linkedln: [marios-kanellopoulos](https://www.linkedin.com/in/marios-kanellopoulos)

Kubilay Caglayan
- Github: [@kubilaycaglayan](https://github.com/kubilaycaglayan)
- Twitter: [@kbcaglayan](https://twitter.com/kbcaglayan)
- Linkedln: [kubilay-caglayan](https://www.linkedin.com/in/kubilaycaglayan/)

# How to Run Code
- Run `git clone git@github.com:mariosknl/private-events.git` in the terminal.
- cd into the directory.
- run `bundle install`
- `rails db:migrate && rails db:seed`
- Run `rails server` in the terminal.

# Usage
- Address bar: `localhost:3000` will take you to sign in page.
- From there you can create new user.
- After you create a new user, you can create new events and invite other people.

# Models
- User
- Event
- Invitation

# Associations
- User can create events and also send invitation to other users.
- A User can only see an event if only it has been invited to. The creator of the event is automatically being invited to that event.
- Invited Users are also able to invite other users to the event.

# Home Page
![private events](https://user-images.githubusercontent.com/60448833/82820778-78b5d480-9eab-11ea-9ac2-c06a3b41d29d.png)

# Automated Test Section
- Used RSpec for browser-side test.
- Used Capybara gem for client-side(integration) tests.

- run rspec in your terminal to run the tests.


# Feature & Issues Section
This is an open source project. Feel free to add your feedback. If, for any reason, this project doesn't work as supposed to be in your computer, create an issue so we can help you out with it. Lastly, you can request for a feature to be added.

[Issue Page](https://github.com/mariosknl/private-events/issues)

# Built With

Ruby on Rails
Git
VS Code
Atom
Bootstrap Framework

# Show your support
Give a star if you like this project!

# Acknowledgments
- The Odin project for the project plan
- https://www.theodinproject.com/courses/ruby-on-rails/lessons/associations

# License
This project is MIT licensed
