---
title: Hashes
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a Hash?

A hash is, like an array, an index of sorts with various slots that can refer to various objects. Unlike an array, however, hash elements don't have to be referred to using a number, but can be labelled using any object.

# What are some examples of information that would be Hashes as opposed to some other data type?

Personal information (name, birthday, gender, address, contact info, etc.), glossary/jargon definitions, the names and job titles of employees of a company, etc.

# How are Hashes and Arrays similar? How are they different?

They are both, in a sense, 'compound' variables, in that they are easy ways to group related objects together. However, Arrays require their elements to be numbered, while hashes only require that they be labelled with some object or another.

# How do you retrieve a particular value from a Hash?

the same way as you would from an array; `hashname['element label']`, where "hashname" is the name of the hash, and "'element label'" is the label assigned to the element in the hash.

# How do you add information to a Hash?

`hashname['new label'] = 'new information'`

# How would you perform an operation on every element inside a Hash?

`hashname.each do |c_element, element|`, followed by the operation you want to perform on each element, with `c_element` referring to it's index label and `element` referring to the object itself.

# How would you change the value of a particular element in a Hash?

By reassigning it; `hashname['element label'] = 'new value'`

# How do you delete an element from a Hash?

`hashname.delete('element label')`

# What happens if you try to retrieve an element from a Hash that does not exist in the Hash?

The program returns the default value, which can be set by using `hashname.default = 'value'`, or when the hash is created with the `.new` operation by giving it an argument. If the default value hasn't been defined, the program will return `nil`.

# How do you determine how many elements are in a Hash?

`hashname.length`