# Button 

> “Buttons allow users to take actions, and make choices, with a single tap.”


CONTENT

* [Design Best Practices](#design-best-practices)
* [Use](#use)
* [Sizes](#sizes)
* [Elevations](#elevations)
* [Types](#Types)




---

## Design Best Practices
#### Aim To 


- Keep your submit-button disabled until all required fields are filled. 
- Validate your input field on leaving it (even though the submit-button is disabled.)

#### Avoid
- ?

## Use

Buttons can either be onCanvas or floating. Buttons that are supposed to be over the keyboard on native have same behavior as floating buttons on all platforms!

## Sizes
Buttons are categorised as Size sm, md (default), lg, xl -> Role (1-4) -> Variation
Size defines height of button and role defines how important the button is where 1 is the most important.



#### XL: 
- Only used for FAB, that is always floating. Only available in primary color.

#### LG: 
- Use sparingly and mostly for messaging states, like empty states, and especially when there is only one button, like alerts. Min-width 220px.

#### MD: 
- Mostly for multiple buttons. Either flexsized or as blocksize. Use “1” for primary action, and 2, 3 or 4 for secondary options. Min width 88px

#### SM: 
- Also used for multiple buttons, but mostly when amount of buttons >2. For example in detail pages where there are up to 3 buttons


## Elevations
Buttons are default set to z0, so if you are using a button on canvas or a card the button is set to z0. However is you need a button to be floating on top of the others elements, then use z8.

## Types

- Text
- Icon 
- Icon + Text
- Text + Icon 
- Toggle Buttons

___
![Icon dont](https://github.com/tja1607/testGuidelines/blob/master/Forms/dont.svg) Don’t overuse putting forms side by sid | ![Icon do](https://github.com/tja1607/testGuidelines/blob/master/Forms/do.svg) Keep the same structure as in real world examples and make it easy for people to copy/paste
-------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------
![Don't do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDont.svg) | ![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDo.svg)
 We're living the future so the present is our past                                   | We're living the future so the present is our past

**Don’t overuse putting forms side by side**

![Don't do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDont.svg)

> We're living the future so the present is our past

**Keep the same structure as in real world examples and make it easy for people to copy/paste**

![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDo.svg)

> We're living the future so

## Input Container

Input Container provides layout and styling of inputs within it as well as styling for:

- the input label
- input description,
- a tag (often used for things like (optional) next to the form label)
- a slot to hold a tooltip or other information pinned to the top right of the container

> ![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/do.svg) We're living the future so