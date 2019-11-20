# Flutter Cat Test Application
![N|Solid](https://cdn2.thecatapi.com/logos/thecatapi_256xW.png)

# App requirements
The application should use the following features/components:
  - [BLoC](https://bloclibrary.dev/#/) should be used for the app architecture (use the library [bloc](https://pub.dev/packages/bloc))
  - The app should have a splash screen with a cat image (free to use any), and should be correctly implemented on both platforms (ios and android)
  - After the splash, if the user was not logged in previously, you have to display a login screen with 2 options: Facebook, Google.
  - After successful login on the home screen, the user will see 3 tabs: Cats, Favorites, Profile. 
On the first tab, you have to fetch the list of cat images from [The CAT API](https://thecatapi.com/) and the same count of facts about the cats by using the [Cat Facts API](https://catfact.ninja/). This screen should display only the list of images and an icon on the bottom right corner which will provide the ability to add the selected item to favourites. 
If the item is already added to favourites the icon should indicate it (something similar like on Instagram like button, if the image liked the heart icon will be filled and coloured). Pagination should be implemented as well. By clicking on any cat image the details page should be displayed with Hero animation, and the Cat Fact should be displayed under the image. The toolbar in the details page should display the "add to favourite" icon as well, so you can add/remove the selected item. The second tab should display the items you add on the first tab. This list should have the same look like the list on the first tab, with the same functionality. So you can remove the items from favourites, open the details page. On the third tab, you should display the user information: avatar in circle image, user name, email (optional), logout button.
  - The app should remember the logged in user, so after a successful login, if the user closes the app and reopen it again, the app should navigate to the home page.
  - Make sure the app looks the same on both ios/android platforms.
