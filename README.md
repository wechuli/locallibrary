# locallibrary
Complete rewrite of local library website on MDN - https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website


Description

      Complete Re-write of the local library website built on MDN but turning it into an api(with django rest framework) instead of using templates

Addition

      -Include some aspects of AI -maybe text anlytics for the library description
      -Include authentication and authorization using jwt. Users should be able to sign up with their emails, use gmail account or their facebook accounts 
      -Extend the user model to include library members and library admins
      -Include email registration and verification for library members
      -Write Tests for the API(I hate doing this :) )
      -Learn how to document APIs by documenting this one
      -Deploy to Heroku or AWS with a managed Postgred instance or consider containers
      
Possible Improvements(Once I know how to do it)


      -Include Image upload for the book covers, and also for the authors
      -Wire up the Image upload to S3 so that all media files are stored and retrived from s3
