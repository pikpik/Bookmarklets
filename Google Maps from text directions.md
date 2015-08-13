Bookmarklet: Google Maps from text directions

1. Bookmark any page

2. Change name: "Gmaps from Text Directions"

3. Change URL: ```javascript:( function () { var places = prompt ( "Paste lines of directions" ).split ( "\n" ).map ( function ( text ) { return encodeURIComponent ( text ); } ).join ( "/" ); window.open ( "https://www.google.com/maps/dir/" + places, "Maps" + Date.now () ); } ) ();```

4. Save the bookmark

5. Copy the lines of directions, click the bookmarklet, and paste
