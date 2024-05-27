Rails interview questions into different concepts and levels:

### ActiveRecord and Database-Related Questions

**Beginner:**
1. What is the difference between `has_many: through` and `has_and_belongs_to_many`, which one is better?
2. Validations in Rails, Lifecycle of an object, when are validations called/checked
3. Migrations in Rails and its uses
4. Types of associations in Rails
5. Scopes in Rails
6. Difference between class methods and scopes (are they similar?) 
7. Strong Parameters
8. Difference between `before_save`, `before_create`, and `before_update`
9. Default Scope
10. Default arguments to controller/actions, where you initiate a new model object
11. Rollback (Specific migration)
12. ActiveRecord Callbacks and Ex, with examples
13. Customer validations in Rails
14. Single Table Inheritance, Advantages, and Disadvantages
15. N+1 query problem, how to resolve N+1 query problem, explain with example
16. The difference between includes and joins
17. self_join associations
18. ORM: Explain
19. Is it possible to change the conventions of the naming of tables, if yes, how and explain an example
20. Relational callbacks, conditional callbacks
21. Transactional callbacks

**Intermediate:**
22. What happens if you do not provide column type in remove_column migration?
23. What happens if you rollback with the change method, a change-column migration.
24. Eager loading the associations
25. Sanitizing params in Rails
26. The difference between ActiveRecord and ActiveModel
27. Difference between dependent: :destroy and :delete_all
28. How to organize controllers and way to make the controllers thin
29. Difference between delete and destroy
30. Find_each in Rails, why Model.all method is not ideal to use for loading all the instances of model at once?
31. Difference between eager load and includes method which one is better
32. Which is faster delete or destroy
33. Yield in Ruby, method containing yield if it is called without a block
34. Hash and HashWithIndifferentAccess
35. Ways to invoke a method (with examples)
36. Different between string and symbols (Ruby)
37. Schema versioning, when it changes
38. Reversible migrations
39. When to use up and down methods instead of change method inside migrations with example
40. Shallow nesting in routes when preferable to use
41. Difference between allow-nil and allow blank validation opts
42. Strid & conditional validations
43. When to skip callbacks, List few methods, by using them we can skip callbacks
44. Is it possible to send emails without rendering a template in Rails?
45. Difference between save and save!
46. Possible to replace schema.rb in Rails, how to do it
47. Difference between ActiveRecord::Relation and Array
48. Advantages of hash over array in Ruby
49. Difference between iterators & loops in Ruby
50. Accessor methods in Ruby, list and explain
51. How to define foreign key into an existing table in Rails
52. Advantages of using Enum over array in Ruby
53. Preferences for return response for an API, JBuilder or ActiveModelSerializers? And why
54. Difference between lambda and proc?
55. Arguments scope, argumented scopes, when we need to write 
56. Difference between update & update-attribute methods
57. Difference between dependent: :destroy and :delete_all
58. Possible to replace schema.rb in Rails, how to do it
59. Find_each in Rails, why Model.all method is not ideal to use for loading all the instances of model at once?
60. Difference between eager load and includes method, which one is better

**Expert:**
61. Polymorphic associations in Rails, when can one use it? When should you use it, what are the disadvantages of using polymorphic associations?
62. Difference between let & let! in RSpec.
63. How to get objects with at least one child?
64. Difference between uniq and distinct
65. What happens if you do not provide column type in remove_column migration?
66. What happens if you rollback with the change method, a change-column migration.
67. Eager loading the associations
68. Content-for in Rails.
69. Sanitizing params in Rails.
70. Render & redirect in Rails.
71. How many versions have you worked with, list changes between Rails versions you have worked on.
72. What are reversible migrations and how to use them?
73. Explain meta-programming in Ruby.
74. Implementing inject in Ruby.
75. Difference between equal? and eql? in Ruby.
76. Advantages of hash over array in Ruby.
77. Difference between iterators & loops in Ruby.
78. Explain the usage of delegate methods in Rails.

### Views and Helpers

**Beginner:**
1. Partials in Rails, usage of partials, ways to pass local variables to operations
2. Helper Class in Rails
3. FormHelpers in Rails, names & difference between them

**Intermediate:**
4. Right time to define helper method inside a controller in Rails
5. Render vs Redirect in Rails

**Expert:**
6. Explain the purpose of the initializers directory in a Rails project

### Controllers and Routing

**Beginner:**
1. Member and collection routes
2. Namespace and scoped routing
3. Routing in Rails
4. filter_action/ Controller callbacks
5. ActiveRecord::RecordNotFound exceptions for all resources

**Intermediate:**
6. Explain difference between before_save, before_create, and before_update?
7. Strong Parameters
8. Default arguments to controller/actions, where you initiate a new model object

**Expert:**
9. Implement an admin backend for a web app solution proposed which solution will you propose: gem or custom admin panel and reasons

### Ruby Language Questions

**Beginner:**
1. Send method in Ruby.
2. Difference between send and public_send in Ruby.

**Intermediate:**
3. Different ways to invoke a method (with examples)
4. Difference between string and symbols in Ruby
5. Yield in Ruby, method containing yield if it is called without a block
6. Hash and HashWithIndifferentAccess

**Expert:**
7. Difference between lambda and proc?
8. Explain metaprogramming in Ruby and provide an example
9. Difference between equal? and eql? in Ruby
10. Explain the Singleton class (eigenclass) in Ruby
11. Inject method in Ruby
12. Difference between class methods and instance methods in Ruby
13. Modules in Ruby, difference between class & instance methods

### Jobs

**Beginner:**
1. Sidekiq: Explain how it works in production and development environments.
2. Difference between sidekiq workers and Rails active jobs.

**Intermediate:**
3. perform & perform_async in Sidekiq (Difference).

**Expert:**
4. Difference between let & let! in RSpec.
5. Rake tasks, how to define and implement custom rake tasks.
6. ActiveStorage? How can you use them?

### Asset Management

**Intermediate:**
1. Webpacker and Sprockets
2. Asset pipeline in Rails

### Advanced Rails Topics

**Intermediate:**
1. Single Table Inheritance, Advantages, and Disadvantages
2. Delegates in Rails, explain the usage of delegates
3. Strong Parameters

**Expert:**
4. Explain the purpose of initializers directory in a Rails project
5. API versioning in Rails? Explain when there is a need to change the version of an API

### Mailers

**Beginner:**
1. Mailers, ways to pass arguments to a mailer

**Intermediate:**
2. Possible to send emails without rendering a template in Rails?

### Security

**Intermediate:**
1. Authentication in Rails using Devise, JWT, and process to do so
2. Session storage in Rails, explain.
3. Session hijacking

### Performance and Optimization

**Beginner:**
1. How to organize controllers and make them thin
2. Find_each in Rails, why Model.all method is not ideal to use for loading all the instances of a model at once?
3. Difference between eager load and includes method, which one is better
4. Difference between delete and destroy

**Intermediate:**
5. N+1 query problem, how to resolve the N+1 query problem, explain with an example
6. Eager loading associations

### Rails Engines and Gems

**Beginner:**
1. Difference between a Gem and a Rails engine.
2. What do we mean by a Rails engine, when we need to use a Rails engine, list gems which are engines as well

**Intermediate:**
3. Gems used for admin backend (better gem & why)

### Testing

**Intermediate:**
1. Difference between let and let! in RSpec

### Miscellaneous

**Intermediate:**
1. Turbolinks in Rails?
2. Page Caching, Action Caching & Fragment Caching?

This categorization should help you understand the different aspects of Rails and Ruby better and prepare you for different levels of interview questions. If you need more detailed answers or further assistance with any specific question, feel free to ask!
