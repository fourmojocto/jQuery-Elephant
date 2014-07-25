## Elephant

The idea behind jQuery Elephant is that forms should be able to store their data locally in the browser without having to worry about a page closure or accidental navigation away causing any problem with the form data being erased. 

Long forms can be very tedious for a user, particularly if they have to enter them in multiple times.

However, as a developer, you don't want to have to weigh your page down with a very heavy library to accomplish this.

jQuery Elephant is 1.8KB uncompressed, and only 934B minified!

**Usage:**

Include the script on your page, _after_ jQuery:

		<script src="jquery.elephant.min.js"></script>

In your document ready, bind to your `form` object directly:

		$("#myForm").elephant();

And that's it.
