# Google Meet Auto Admit

This script will automatically admit user into a Google Meet

# Bookmarklet

```
javascript:(function()%7Bfunction%20autoAdmit()%20%7Bfor%20(let%20element%20of%20document.getElementsByTagName('span'))%20%7Bif%20(element.innerHTML%20%3D%3D%3D%20'Admit')%20%7Bconsole.log('There%20is%20someone%20waiting%20to%20join%20this%20meeting%2C%20automatically%20admitting%20them...')%3Belement.click()%3B%7D%7D%7Dalert('Enabling%20Auto%20Admit')%3Bconsole.log('Enabling%20Auto%20Admit')%3BsetInterval(autoAdmit%2C%205%20*%201000)%7D)()
```
