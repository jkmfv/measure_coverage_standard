# Test result


|  Test cases 	| command  	|  Result 	|
|---	|---	|---	|---	|---	|
|  TC1 	|  `bundle exec rspec spec/tc1.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 4 / 5 LOC (80.0%) covered. 	|
|  TC2 	|  `bundle exec rspec spec/tc2.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 4 / 5 LOC (80.0%) covered. 	|
|  TC3 	|  `bundle exec rspec spec/tc3.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 4 / 5 LOC (80.0%) covered. 	|
|  TC1 + TC2 	|  `bundle exec rspec spec/tc1.rb spec/tc2.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 11 / 11 LOC (100.0%) covered 	|
|  TC1 + TC3 	|  `bundle exec rspec spec/tc1.rb spec/tc3.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 11 / 11 LOC (100.0%) covered. 	|
|  TC2 + TC3 	|  `bundle exec rspec spec/tc2.rb spec/tc3.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 10 / 11 LOC (90.91%) covered. 	|
|  TC1 + TC2 + TC3 	|  `bundle exec rspec spec/tc1.rb spec/tc2.rb spec/tc3.rb` 	|  Coverage report generated for RSpec to /measure_coverage_standard/ruby/coverage. 17 / 17 LOC (100.0%) covered 	|
