console commands
create
case 1 : <command> <Class> <arg 1> ... <arg n> 
case 2 : <Class> <command> <arg 1> ... <arg n> 
case 3 : <command> <Class>(<arg 1> ... <arg n>) 
case 4 : <Class> <command>(<arg 1> ... <arg n>) 
case 5 : <Class>.<command>(<arg 1> ... <arg n>) 
case 3 : <command>.<Class>(<arg 1> ... <arg n>) 

examples
create User name="dennis"
User create name="dennis"
create.User name="dennis"
User.create name="dennis"
create User (name="dennis")
User create (name="dennis")
create.User (name="dennis")
User.create (name="dennis")
