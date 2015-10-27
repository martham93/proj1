# Q0: Why is this error being thrown?
The error was being thrown because I forgot to complete a migration. 

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
Random Pokemon are appearing because Rails Magaic (the rake db:seed). The common factor between all of the Pokemon is that they are wild. 

# Question 2a: What does the following line in the help text do? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
Through, rails magic, this line of code  <%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>" allows a new Pokemon to be added the protal of whichever user is signed in. 

# Question 3: What would you name your own Pokemon?
Ruby

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
Into redirect_to I passed in trainer_path(params[:trainer]). It was a path that needed all of the information contained in the trainer. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
This allows an error message to appear on the form because views/layouts/application.html.erb is rendering something at the very end. Rails will use views/layouts/application.html.erb since there is no controller specific layout 

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
