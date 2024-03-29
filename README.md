# Search select multiple

![Default appearance for the search-select-multiple field plug-in](extras/default-search.jpg)

## Description

This field plug-in adds the ability to filter choice list options for a *select_mutiple* field. Filter by entering search text into the search field. Also see the sibling field plug-in, [search-select_one](https://github.com/surveycto/search-select-one/blob/master/README.md).

[![Download now](extras/download-button.png)](https://github.com/surveycto/search-select-multiple/raw/master/search-select-multiple.fieldplugin.zip)

## Features
* Provides a text box for searching a list of options.
* Works with [preloaded choices](https://docs.surveycto.com/02-designing-forms/04-sample-forms/12.search-and-select.html).

### Requirements
*Requires Android 6 or upwards to work on SurveyCTO Collect.*

## Data format
This field plug-in uses requires the `select_multiple` field type. The data is stored as you would expect from this field type without a field plug-in.

## How to use
### Getting started

1. Download the [sample form](https://github.com/surveycto/search-select-multiple/raw/master/extras/sample-form/sample-form.zip) from this repo and upload it to your SurveyCTO server.
1. Download the [search-select-multiple.fieldplugin.zip](https://github.com/surveycto/search-select-multiple/raw/master/search-select-multiple.fieldplugin.zip) file from this repo, and attach it to the test form on your SurveyCTO server.

### Default SurveyCTO feature support

| Feature / Property | Support |
| --- | --- |
| Supported field type(s) | `select_multiple`|
| Default values | Yes |
| Custom constraint message | Yes |
| Custom required message | Yes |
| Read only | Yes |
| media:image | Yes |
| media:audio | Yes |
| media:video | Yes |
| `minimal` appearance | No |
| `compact` appearance | No |
| `compact-#` appearance | No |

This field plugin started with the [baseline-select_multiple field plug-in](https://github.com/surveycto/baseline-select_multiple) as a template and inherits the listed [expanded features](https://github.com/surveycto/baseline-select_multiple#expanded-feature-support) supported by the baseline field plugin.

## More resources

* **Sample form**  
You can find a sample form definition here: <br>
[Download sample form](https://github.com/surveycto/search-select-multiple/raw/master/extras/sample-form/sample-form.zip)

* **Developer documentation**  
Instructions and resources for developing your own field plug-ins.  
[https://github.com/surveycto/Field-plug-in-resources](https://github.com/surveycto/Field-plug-in-resources)

* **User documentation**  
How to get started using field plug-ins in your SurveyCTO form.  
[https://docs.surveycto.com/02-designing-forms/03-advanced-topics/06.using-field-plug-ins.html](https://docs.surveycto.com/02-designing-forms/03-advanced-topics/06.using-field-plug-ins.html)
