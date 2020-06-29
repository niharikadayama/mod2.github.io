<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 200px;
  font-family:helvetica;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 992px) {
  .column {
    width: 100%;
  }
 @media screen and (max-width: 991px) {
  .column {
    width: 50%;
  }
 @media screen and (max-width: 767px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>
<h2 style="font-family: sans-serif;">MY POETRY COLLECTION</h2>
<div class="row">
  <div class="column" style="background-color:lightpink;">
    <h2>The Road Not Taken</h2>
    <p>
      I shall be telling this with a sigh<br>
      Somewhere ages and ages hence:<br>
      Two roads diverged in a wood, and I<br>
      I took the one less traveled by,<br>
      And that has made all the difference.<br>
    </p>
  </div>
  <div class="column" style="background-color:lightgreen;">
    <h2>Three Songs</h2>
    <p>
   Come unto these yellow sands,<br>
   And then take hands:<br>
   Court'sied when you have, and kiss'd,<br>
   The wild waves whist<br>
   Foot it featly here and there;<br>
   And, sweet sprites, the burthen bear.<br>
    </p>
  </div>
  <div class="column" style="background-color:lightblue;">
    <h2>I'm Nobody! Who are you?</h2>
    <p> 
   I'm Nobody! Who are you?<br>
   Are you – Nobody – too?<br>
   Then there's a pair of us!<br>
   Don't tell! they'd advertise – you know!<br>
    </p>
  </div>
</div>

</body>
</html>
