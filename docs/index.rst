=====
A Documentation Sample
=====
Plain text
----------
Titles are underlined (or over-
and underlined) with a printing
nonalphanumeric 7-bit ASCII
character. Recommended choices
are "``= - ` : ' " ~ ^ _ * + # < >``".
The underline/overline must be at
least as long as the title text.

A lone top-level (sub)section
is lifted up to be the document's
(sub)title.

Paragraphs
----------
This is a paragraph.

Paragraphs line up at their left
edges, and are normally separated
by blank lines. 

Bullet Lists
------------
Bullet lists:

- This is item 1
- This is item 2

- Bullets are "-", "*" or "+".
  Continuing text must be aligned
  after the bullet and whitespace.

Note that a blank line is required
before the first item and after the
last, but is optional between items. 

Enumerated lists
----------------
Enumerated lists:

3. This is the first item
4. This is the second item
5. Enumerators are arabic numbers,
   single letters, or roman numerals
6. List items should be sequentially
   numbered, but need not start at 1
   (although not all formatters will
   honour the first index).
#. This item is auto-enumerated 

Definition Lists
----------------
Definition lists:

what
  Definition lists associate a term with
  a definition.

how
  The term is a one-line phrase, and the
  definition is one or more paragraphs or
  body elements, indented relative to the
  term. Blank lines are not allowed
  between term and definition.

Field Lists
-----------
:Authors:
    Joby Chacko,
    Author 2

    (and sundry other good-natured folks)

:Version: 1.0 of 2001/08/08
:Dedication: Restructure Documentation. 

.. toctree::
    :hidden:

    docs/configuration
