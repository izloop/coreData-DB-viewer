# CoreData DB list viewer
A simple 'script' which is inserted in the AppDelegate file within didFinishLaunchingWithOptions which allows the developer to see the list of stored items in the CoreData model. Best used with an Third Party app such as in my case Datum.

 `let urls = FileManager.default.urls(for: .documentDirectory, in: .userDomainMask)`
        
  `print(urls[urls.count-1] as URL)`
  
  ![alt text](https://i.imgur.com/rvXXxav.png)
