This project was completed as part of the (Winter 2022 - Shopify)

# Specifications
The assignment description provided the following specifications, although we did not accomplish all of them.

Image Application features to include:_
_* Users create accounts
_* Users can add, edit, delete images (but only their own)
_* Simple image search feature
_* Basic ui similer to the application existing
_* Users have a profile page (users#show) with a list of all the photos they are tagged in_
_* Users can "Bookmark" images; include image favorites on profile page_
_* Users can add, edit, delete comments to images_
_* Used cloudnery cloud as a repositery of images

# Technologies Used
* Ruby 2.5.4, Rails 5.2, Bundler, Postgres
* Gems added manually after initial project setup: Capybara, jquery-rails, faker, bootstrap-sass, sassc-rails, rspec-rails

# Project Setup instructions
1. Ensure that you have the correct versions of Ruby, Rails, and PSQL installed.
2. Clone the project locally from github (https://github.com/pradeeprao22/.
3. Install Bundler if you do not already have it by running **gem install bundler** in the terminal.
4. Run **bundle install** to manage gems; if you make additional changes to the Gemfile, you will need to run this command again.
5. Run **rake db:create**, which should create two databases (for development and testing).
6. Run **rake db:migrate**, followed by **rake db:test:prepare**.
7. Enter **rails s** or **rails server** at the terminal prompt.
8. Open a browser window and type **localhost:3000** in the address bar.

If something doesn't display correctly or goes wrong somehow, please contact me at pradeep.rao@londevs.com and I will do my best to troubleshoot for you.

# Known Issues and Limitations
No known issues per se, but limited functionality.
