# Instructions
Go to a directory of your choice, then run the script by doing:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/maneater2/dwm-patch-selector/main/dps.sh)"
```
Your dwm build will be in the final-src directory.
# How does this script work?
It clones the [dwm-flexipatch](https://github.com/bakkeby/dwm-flexipatch)
and [flexipatch-finalizer](https://github.com/bakkeby/flexipatch-finalizer)
repositories, and gives you a choice of what patches you want to use in your dwm build.
Then it enables those patches and strips [dwm-flexipatch](https://github.com/bakkeby/dwm-flexipatch) of unnecessary patches you didn't select.
