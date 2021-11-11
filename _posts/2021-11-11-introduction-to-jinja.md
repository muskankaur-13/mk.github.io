INTRODUCTION TO JINJA

What is Jinja? 

Jinja is a Template Engine. Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document. It reuses static web page elements. Such languages essentially contain variables as well as some programming logic, which when evaluated (or rendered into HTML) are replaced with actual values. Jinja templates use {% ... %} for expressions or logic (like for loops), while {{ ... }} is used for outputting the results of an expression or a variable to the end user. The latter tag, when rendered, is replaced with a value or values, and is seen by the end user. Jinja Templates are just .html files. 

 It includes:

-> Template inheritance and inclusion. 

-> Define and import macros within templates. 

-> HTML templates can use autoescaping to prevent XSS from untrusted user input. 

-> A sandboxed environment can safely render untrusted templates. 

-> Async support for generating templates that automatically handle sync and async functions without extra syntax. I18N support with Babel. 

-> Templates are compiled to optimized Python code just-in-time and cached, or can be compiled ahead-of-time. 

-> Exceptions point to the correct line in templates to make debugging easier. 

-> Extensible filters, tests, functions, and even syntax. 


Jinja’s philosophy is that while application logic belongs in Python if possible, it shouldn’t make the template designer’s job difficult by restricting functionality too much. 
