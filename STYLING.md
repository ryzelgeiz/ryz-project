# Styling

- [Introduction](#Introduction)
- [Block Element Modifier](#Block-Element-Modifier)
- [Naming](#Naming)
  - [Block](#Block)
  - [Element](#Element)
  - [Modifier](#Modifier)
- [Key benefits of BEM](#Key-benefits-of-BEM)

## Introduction
BEM is a highly useful, powerful, and simple naming convention that makes your front-end code easier to read and understand, easier to work with, easier to scale, more robust and explicit, and a lot more strict.

## Block Element Modifier
BEM stands for Block Element Modifier and is an HTML & CSS naming methodology that helps you create reusable components and aids code sharing in frontend development and brings a system approach in your project and keeps it from the mess. 

## Naming
You will not be surprised to hear that BEM is an abbreviation of the key elements of the methodology — Block, Element and Modifier. BEM’s strict naming rules can be found [here](http://getbem.com/naming/).

BEM methodology allows you to change the naming convention, choose the most convenient file structure or add any technologies you want to the block. And it provides a robust convention for naming your CSS classes as independent modules.

There are a few variations of the methodology, but the most common approach is this:

```
.block {}
.block__element {}
.block__element-modifier {}
```

### Block
> Standalone entity that is meaningful on its own or represents an object on your website.

Examples :
`header`, `container`, `menu`, `checkbox`, `input`

### Element
> A part of a block that has no standalone meaning and is semantically tied to its block or a component within the block that performs a particular function.

Examples :
`menu item`, `list item`, `checkbox caption`, `header title`

### Modifier
> Any variations of a block or element. Use them to change appearance or behavior.

Examples :
`disabled`, `highlighted`, `checked`, `fixed`, `size big`, `color yellow`

![BEM](http://getbem.com/assets/github_captions.jpg)


## Key benefits of BEM
* **Reduces risk :** BEM provides isolated components that support modular design. Using BEM you can develop each a component in isolation with no risk of missing styles or instigating unintended consequences.<br/>
You also get the ability to transfer blocks from your finished projects to new ones.
* **Helps teams collaborate :** BEM provides you with robust CSS conventions that enables everyone to work to the same standards making it better for collaboration, especially when different teams are working on their own blocks.<br/>
With a set of style guidelines in place, you can build a library of blocks, making your CSS super effective.
* **Easier to maintain :** BEM allows for phased migration as blocks or templates are updated. Future updates can be done safely, as you know new styles will only target blocks using specified styles.<br/>
Because BEM methodology gives your CSS code a solid structure that remains simple and easy to understand.
* **Reusability :** Composing independent blocks in different ways, and reusing them intelligently, reduces the amount of CSS code that you will have to maintain.
With a set of style guidelines in place, you can build a library of blocks, making your CSS super effective.

---









