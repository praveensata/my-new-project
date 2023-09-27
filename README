# N-dimensional-Nearest-Neighbours (NNN)
# MY FIRST PROJECT
# Building AI course project

<!-- CREDIT: I have used the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. -->

## Summary
Given an (N-1)-dimensional array, return the top M "nearest neighbours" amongst the thousands of previously known arrays, with an estimate (or a range) for the N-th element.

## Background
Product companies (e.g., manufacturers) might use a significant number of parameters (N-1) to describe a single product, whose N-th element is, e.g., its price.
When they receive a new project/product request, they have to generate the whole N-dimensional array for it. In some cases, they have to produce quickly an estimate for the
N-th parameter. This task is daunting if not impossible without an efficient/automated db consultation.
Sometimes, part of the team knowledge might get lost (e.g., if a member leaves) and a new product code might be released unnecessarily,
just because they couldn't interrogate the db properly and know that the project/product had been requestd before.

Problem solved:
* Prevent product duplication in the db, by finding any pre-existing exact match
* Find M nearest neighbours and return their arrays and N-th elements
* Speed up the quotation process providing a price estimate (range, average, median, etc) based on previous quotations

## How is it used?
The NNN would be used as part of the quotaion process:
* Sales sends a qualified request to Bid & Price/Product Management (BP/PM)
* BP/PM triages the request and gets to a strawman solution (including draft BOM)
* The BOM is then represented as a (N-1)-dimensional array and used to interrogate the db
* NNN Solutions is applied
* M similar products are returned, with the associated information on price

<!--- Images will make your README look nice! Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.) ![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg) If you need to resize images, you have to use an HTML tag, like this: <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300"> 
This is how you create code examples: --->
```
def main():
   # no code yet
main() 
```

## Data sources and AI methods
Data is the BOM db, is proprietary, and resides in the Company's ERP.

<!--- If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        | --->

## Challenges
NNN applies the nearest-neighbour method to find existing products that are similar to the newly requested.
Human touch will be needed to critically interpret the algorithm output and make a final commercial decision on what price to propose.
Challenges:
* existing data might be missing of some elements (e.g., N-dimensional arrays with some naught/empty element)
* high number of arrays (3-4000) of significant size (N = 25/30+)
* arrays are strings; i.e. how do you define the 'distance' between them?

## What next?
The project is yet to start. I'd need help from some brilliant mind with more time at their disposal than I have.
It might be subsequently improved with a nice UI/UX for ease of use, with more accurate price estimations or even become "prescriptive" (e.g., making the price) in some cases

## Acknowledgments
* Reaktor Innovations and University of Helsinki: this project is part of their Building AI course
<!--- list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
view raw --->
