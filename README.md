[rails-assets]() and [fullpage.js bower package]() are not working together

How I tried to setup:

1. Added the following content on Gemfile:
    ```ruby
source 'https://rails-assets.org' do
  gem 'rails-assets-fullpage.js'
end
```

2. Added the `fullpage.js` bower package name on both application.js and application.css

3. Tried to access localhost on browser and got:
    ![](https://dl.dropboxusercontent.com/spa/9kycf4oxo6l3hcj/yib_tkiu.png)

4. Removed the entry from application.css to see if the js entry at least was working, but got:
    ![](https://dl.dropboxusercontent.com/spa/9kycf4oxo6l3hcj/p3_jeils.png)

    **Notice it's actually loading the css content in a file that was supposed to be a js**
