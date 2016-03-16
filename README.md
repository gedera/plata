# Plata

Rails gem to describe a number in words for *English* and *Spanish*. For use english and spanish simply define:

  I18n.locale = :en (English)
  I18n.locale = :es (Espanish)

Ideal to be used to print in receipts.

## Install

Add the following line in to your Gemfile:
```ruby
     gem 'plata'
```

Or from github:
```ruby
     gem 'plata', :git => 'git://github.com/gedera/plata.git'
```

And from the command line run:
```console
    $ bundle
```

## Usage

Examples for return numbers in *english* and *spanish*:
```ruby
     > 9736.humanize
     "nine thousand seven hundred thirty six" (English)
     "nueve mil setecientos treinta y seis" (Spanish)
```
```ruby
     > 9736.45.humanize
     "nine thousand seven hundred thirty six with 45/100" (English)
     "nueve mil setecientos treinta y seis con 45/100" (Spanish)
```

Enjoy!!!

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/plata.
