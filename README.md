# BUI---Better-UI-Interactions
Better UI interactions for macrodroid

Are you tired of using delays in your touch macros? Tired of waiting until a button apears just for the macro to not press it? Want a way to use magic text for the UI interaction action? BUI solves everything.

# How it works
## Input variables
BUI its an action block with input variables that allow you to controll everything you need:
* type: What type of interaction (only click is suported now)
* method: How the block knows where to click (coordinates, id, or text)
* click coordinates X and Y: The coordinates on where the action block will click (only if method is coordinates)
* text: The text the block will click (only if method is text)
* skip: How many texts the block will skip (only if method is text)
* click id: What id will the block click (only if method is id)

## Wait until finished
When the "Wait until finished" checkbox is checked, the action block will keep trying to click forever until the button apears and it clicks it, this is really usefull for touch macros
