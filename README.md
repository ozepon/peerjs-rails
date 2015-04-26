# Peerjs::Rails

Asset Pipline wrapper, for awesome [PeerJS](https://github.com/peers/peerjs), version `0.3.9`

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'peerjs-rails'
```

And then execute:

    $ bundle

Now you are able to add this awesome feature into your product by adding
following into your `application.js` file:

```js
//= require peer
```

## Usage

<!-- TODO: Write usage instructions here -->

get SkyWayAPIKEY<br>
[SkyWay](http://nttcom.github.io/skyway/)

chage directory

		$cd {your aplication`s name}

create controller

		$ rails g controller peer

root.rb

```ruby
root 'peer#index'
```

app/controllers/peer\_controller.rb

```ruby
def index
end
```

create view

```
		$touch app/views/peer/index.html.erb
```

app/views/peer/index.html.erb

```ruby
TODO: usage 

```

[PeerJs support browser](http://peerjs.com/status/)


## Contributing

1. Fork it ( https://github.com/shemerey/peerjs-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
