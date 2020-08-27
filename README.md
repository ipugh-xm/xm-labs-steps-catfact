# Catfact Steps

This step allows you to get cat facts from catfact.ninja/fact.

---------

<kbd>
<a href="https://support.xmatters.com/hc/en-us/community/topics">
   <img src="https://github.com/xmatters/xMatters-Labs/raw/master/media/disclaimer.png">
</a>
</kbd>

---------

# Files

* [CatfactSteps.zip](CatfactSteps.zip) - Workflow zip file with the step and example flow
* [cat.png](/cat.png) - cat

# How it works
This step uses the catfact.ninja website to get a random catfact


# Installation

## xMatters Setup
1. Download the [CatfactSteps.zip](CatfactSteps.zip) file onto your local computer
2. Navigate to the Workflows tab of your xMatters instance
3. Click Import, and select the zip file you just downloaded


## Usage
The **Catfact - cat fact** step requires that an endpoint to the website `https://catfact.ninja/fact` be available. Create the endpoint with no authentication and use in the step when putting it on the canvas.

### Outputs

| Name | Description |
| ---- | ----------  |
| fact | Cat fact! |


## Example
This is an example of getting a cat fact

<kbd>
	<img src="/media/ExampleFlow.png">
</kbd>

