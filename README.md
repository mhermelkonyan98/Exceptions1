# Exceptions1

You are required to extend the existing code so that it handles std::invalid_argument exception properly. More specifically, you have to extend the implementation of process_input function. It takes integer  as an argument and has to work as follows:

1. It calls function largest_proper_divisor(n).
2. If this call returns a value without raising an exception, it should print in a single line result=d where  is the returned value.
3. Otherwise, if the call raises a std::invalid_argument exception, it has to print in a single line the string representation of the raised exception, i.e. its message.
4. Finally, no matter if the exception is raised or not, it should print in a single line returning control flow to caller after any other previously printed output.
To keep the code quality high, you are advised to have exactly one line printing returning control flow to caller in the body of process_input function.
