# A sample Gemfile
source "http://rubygems.org"

gem "rake"
if spade_path = ENV["SPADE_PATH"]
  gem "spade", :path => spade_path
else
  gem "spade"
end
gem "uglifier"

if abbot_path = ENV["ABBOT_PATH"]
  gem "sproutcore", :path => abbot_path
else
  gem "sproutcore", :git => "git://github.com/wycats/abbot-from-scratch.git"
end

