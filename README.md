# memorygame
Memory game like NoPixel for any framework

# Usage

Put the folder in your resources and start in resources.cfg
``ensure vt-memorygame``

# How to use export

```
    -- correctBlocks = Number of correct blocks the player needs to click
    -- incorrectBlocks = number of incorrect blocks after which the game will fail
    -- timetoShow = time in secs for which the right blocks will be shown
    -- timetoLose = maximum time after timetoshow expires for player to select the right blocks
 exports["vt-memorygame"]:thermiteminigame(10, 3, 3, 10,
    function() -- success
        print("success")
    end,
    function() -- failure
        print("failure")
    end)
```
