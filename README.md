# Gosling API Example

This repository describes an example of using APIs of [Gosling.js](https://gosling.js.org) in a React application.

![May-18-2021 09-49-11](https://user-images.githubusercontent.com/9922882/118662979-6caedb00-b7be-11eb-8c8f-15e01ad4a9dc.gif)

## API

This repository uses APIs for quick and easy navigation to genomic locations:

```js
// Navigate to a particular gene
gosRef.current.api.zoomToGene(
   "detail-view", // ID of a gosling view
   gene, // gene symbol (e.g., MYC)
   duration // duration of animated transition
);

// Navigate to a particular genomic location
gosRef.current.api.zoomTo(
   "overview", 
   pos, // e.g., "chr1" or "chr1:1-10000"
   duration
);
```

## Development

Use the following commands to install all packages and run the application in your browser:

```sh
yarn
yarn start
```
