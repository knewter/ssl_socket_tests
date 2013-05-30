# Just some SSLSocket tests on my path to wss://

To run the pure ruby tcp server, taken from ruby/ruby:

    ruby pure_ruby.rb

Then connect to it in another terminal with:

    openssl s_client -connect 127.0.0.1:2000
