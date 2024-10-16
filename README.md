<!DOCTYPE html>
<html lang="en">
 <head>
  <meta charset="UTF-8" />
  <meta
   name="viewport"
   content="width=device-width, initial-scale=1.0" />
  <title>
   Activity 20: Research BEM - Block, Element, Modifier - Architecture
  </title>
  <style>
   /* Block */
   .button {
    padding: 10px 20px;
    border-radius: 4px;
   }

   /* Element */
   .button__icon {
    margin-right: 10px;
   }

   /* Modifier */
   .button--primary {
    background-color: #008000;
    color: white;
   }

   .button--secondary {
    background-color: gray;
    color: black;
   }

   .button--success {
    background-color: #f8b7f6;
    color: white;
   }
  </style>
 </head>
 <body>
  <button class="button button--primary">
   <i class="button__icon"></i>
   Primary
  </button>
  <button class="button button--secondary">
   <i class="button__icon"></i>
   Secondary
  </button>
  <button class="button button--success">
   <i class="button__icon"></i>
   Success
  </button>
 </body>
</html>