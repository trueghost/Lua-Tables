# Lua-Tables
to run use 'lua program_name.lua'

ipairs: ipairs is used to iterate over elements of a sequential table 
(an array-style table with consecutive numeric keys starting from 1). 
It only considers numeric keys and iterates in the order they appear in the table.

pairs: pairs is used to iterate over all key-value pairs in a table, 
regardless of the key type (numeric or non-numeric). 
It does not guarantee any specific order for traversal, 
so the order of iteration may not match the order of insertion.