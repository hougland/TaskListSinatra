source "https://rubygems.org"

ruby "2.2.3"
gem "sinatra"

group :production do
  if ENV["DATABASE_URL"]
    gem "pg"
  end
end

group :development do
  gem "pry"
  gem "sqlite3"
end
