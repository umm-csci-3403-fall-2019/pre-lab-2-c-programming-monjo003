# Leak report

When the Char strip was called and was not freed after it was used, that caused the memory leak.But  by freeing the memory after "cleaned" was used, I was able to fix the code_

