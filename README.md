# Rails Application Technical Test

[![Build Status](https://travis-ci.org/frisoft/rails-app-test.svg?branch=master)](https://travis-ci.org/frisoft/rails-app-test)
[![Code Climate](https://codeclimate.com/github/frisoft/rails-app-test/badges/gpa.svg)](https://codeclimate.com/github/frisoft/rails-app-test)
[![Coverage Status](https://coveralls.io/repos/github/frisoft/rails-app-test/badge.svg?branch=master)](https://coveralls.io/github/frisoft/rails-app-test?branch=master)

This is the Rails application to use as the foundation for the technical test.
Fork this repository and follow the instructions.

### Tasks

* Create a JSON API for saving new properties in the database. It must accept a `params` hash like the following one. It must return the saved properties with their new IDs in JSON format.
Is should be able to receive both a singular property hash and an array of multiple property hashes.

```ruby
{
  properties: [
    {
      address: '102 Whittle Ct, Milton Keynes, MK5 8FT',
      price: '220000'
    },
    {
      address: '128 Savill Lane, Westcroft, Milton Keynes, MK4 4EN',
      price: '150000'
    }
  ]
}
```

* Create a JSON API endpoint for reading a specific property.
* Create a JSON API endpoint for searching properties by postcode efficiently.
* Protect the API with a constant API KEY.

The application can save the information in any way but the information must be presented in the format shown in the example.

### Time

The test should not take more than 4 hours. We will measure time spent as the time between your first and your last commit.

### Testing

Use [RSpec](https://relishapp.com/rspec) and follow a TDD/BDD approach.


### Commit History

We will use your commit history to evaluate your approach to the problem. Please, commit early and often and follow the best practices.

### Code quality indicators

Configure [CodeClimate](http://codeclimate.com), [Travis CI](travis-ci.com) and [Coveralls](https://coveralls.io) and update the provided badges at the beginning of this document.

### Tips

* Follow best practices
* Follow SOLID principles
* Design patterns
