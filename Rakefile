require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "aproxacs-s3sync"
    gem.summary = %Q{Fork of s3sync to be compatible with ruby 1.9.}
    gem.email = "aproxacs@gmail.com"
    gem.homepage = "http://s3sync.net"
    gem.authors = ["aproxacs"]
    gem.files.include FileList.new('lib/**/*.rb', "bin/*",
      "History.txt", "PostInstall.txt", "VERSION", "README.rdoc", "Rakefile")

    gem.executables = ["s3sync", "s3cmd"]
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end

rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end
