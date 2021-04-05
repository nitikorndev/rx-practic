# Appsynth iOS Assignment 

## (${Deadline})
## Confidental
Please don't disclose this assignment with anyone. 

## Story and Goals
We plan to launch a mini Github app. Your responsibility is to create the project's base structure and start the first user profile screen with repository list. It's going to be a long term project so the structure should be flexible, easy to understand and easy to be supported by your team members. Since we are making a high-quality application, we should handle all possible cases properly (no internet connection, showing loading progress)

## Your task
  Your task is to create the user profile screen. The top section shows the profile information and the bottom part shows the user repository list then if user click on a repository. The app will bring the user to the commited list of master branch.

  Before you get the response from API, you need to show the loading progress. In case of any connection issue, you need to show a no connection screen that includes the "no connection" message and "try again" button. By clicking on "try again" button, it will load the data again.

The app should support both landscape and portrait modes. You can use the screenshots below as a reference.

**[Important]** Your final UI can look different, but it should include the same information as on the screenshots.

<img src="screenshots/ss1.png" width="40%"/> <img src="screenshots/ss2.png" width="40%"/> 

Figma: https://www.figma.com/file/LxIBqOv8EaafCHlIPw33Bs/Dev-Assignment---Github

## API details

To get the user profile information
```
GET https://api.github.com/users/defunkt
```

To get the user repository list
```
GET https://api.github.com/users/defunkt/repos
```

To get the commited list of master branch
```
https://api.github.com/repos/defunkt/{repository name}/branches/master
```

## Code requirements
 * The app should be written in Swift 5.0 and later version
 * We prefer MVVM architecture with RxSwift, but you can use MVP or Clean Architecture
 * We prefer to use a dependency injection framework
 * We prefer scalable, maintainable and testable code
 * Having Unit tests would be a plus but not required
 * Having database cache would be a plus but not required
  
## Submission process
  You can use this repository while you are developing the app. 
  
  To submit the test assignment please **close the issue "Assignment Done" in "issues" tab**.
  
  We will review the code **only after you close "Assignment Done" issue**.

