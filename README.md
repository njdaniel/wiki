# Wiki

## Getting started

	$ go build
	$ ./wiki
	
Go to localhost:8080/view/pagename

If it doesnt exist, edit page will show, allowing to save text to be saved. 
Visiting the page again will show the page.

## edit

To edit existing page:
localhost:8080/edit/pagename


## Cleanup

	$ go clean
	
## TODO
1. add links to other pages. 
```<a href="/view/PageName">PageName</a>```
maybe use regexp.ReplaceAllFunc
2. templates/ folder
3. save data to git? lfs https://git-lfs.github.com/