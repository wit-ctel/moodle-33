# Load DSL and Setup Up Stages
require 'capistrano/setup'

# Includes default deployment tasks
require 'capistrano/deploy'

require 'capistrano/git'
require './config/lib/capistrano/submodule_strategy'

# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('config/lib/capistrano/tasks/*.cap').each { |r| import r }
