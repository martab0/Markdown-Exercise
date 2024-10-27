# Title <!-- omit in toc -->

- [Visual elements (heading level 1)](#visual-elements-heading-level-1)
  - [Bold (heading level 2)](#bold-heading-level-2)
  - [Italic](#italic)
  - [Quote](#quote)
  - [Code and formulas](#code-and-formulas)
    - [Code frase](#code-frase)
    - [Formula](#formula)
    - [Code block](#code-block)
    - [Formula block](#formula-block)
- [Linking elements](#linking-elements)
  - [Links to content](#links-to-content)
    - [External](#external)
    - [Internal](#internal)
  - [Images](#images)
    - [External](#external-1)
    - [Internal](#internal-1)
- [Lists](#lists)
  - [ordered](#ordered)
  - [unordered](#unordered)
- [Tables](#tables)


This is the first paragraph of my file.

This is the second paragraph of my file.

This is the trird paragraph of my file.  
This is the fourth paragraph of my file.  
This is the fifth paragraph of my file.

## Visual elements (heading level 1)

### Bold (heading level 2)

This is **bold** text.

### Italic

This is *italic* text written in Markdown as: \*italic* 

### Quote

This is a quote:
> This is a quote.  
 This is a second quote in the same box.

 > This is a third quote.

 ### Code and formulas

#### Code frase

This is a text with `void` code phrase. Can be used to highlight text by presenting it as a box.

#### Formula

This is a formula: $a+b=c$


#### Code block

This is a code block:

```
  <data name="ErrorHeader" xml:space="preserve">
<value>Error</value>
</data>
 ```

#### Formula block

 This is a formula block:
 
  $$  a+b=c  $$
 

 ## Linking elements

 ### Links to content

 #### External

 Example: https://www.meteo.pl/
 
 [Weather forecast](https://www.meteo.pl/ "click here")

 #### Internal

 Link to file example: [additional information](reference.md "click here")

 ### Images

 #### External

![random image](https://picsum.photos/100 "random picture")

 #### Internal

  Note: There can be no spaces in file paths and names.
 
 
 ![bread](Easy_white_bread.jpg "jpg directly in repository")

 Bad practice:
 
 when trying to add picture from outside the repository:  
 \!\[jpg_with_path_outside_repository](../../../Desktop/Z_pulpitu/swans.jpg)  
picture can't be shown:  
 ![jpg_with_path_outside_repository](../../../Desktop/Z_pulpitu/swans.jpg)  
 
 
Good practice:
![path_within_repository](../Markdown-Exercise/Photos/swans.jpg "jpg inside repository folder")

## Lists

### ordered

 1. Point 1
 2. Point 2
 3. Point 3  
    1.  Point 1 (level 2)
    2.  Point 1 (level 2)
 1. Point 4 but written as  1. in Markdown  (avoid - bad practice)
   
### unordered

- first bullet
- second bullet
- another bullet

## Tables

| Column 1           | Column 2                   | Column 3                       |
| ------------------ | -------------------------- | ------------------------------ |
| Row 1              | Row 1                      | Row 1                          |
| Row 2              | Row 2                      | Row 2                          |
| Very long sentence | Another very long sentence | Yet another very long sentence |

Empty row after every table!

