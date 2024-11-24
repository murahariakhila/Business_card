Understanding the code for making business card using kotlin
Created necessary imports and created class main activity
created a function called greeing and a box for image and the text below it.
created image and inserted the image through
  painter = painterResource(R.drawable.email_24dp_e8eaed),
  and created the necessary things for image which makes the image section look like 
  mage(
            painter = painterResource(R.drawable.email_24dp_e8eaed),
            contentDescription = null,
            contentScale = ContentScale.Fit,
            modifier = Modifier
                .fillMaxWidth()
                .height(400.dp)
                .padding(top = 200.dp)
        )
next created a box for the full name and email text.
created a column so that the both texts wont overlap.
next for the contact information below it created a column at top followed by image and text beside it.
created row for each image and text to place them beside each other.
wraped up with the preview section.
