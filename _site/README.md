## Update the pages

1. Update **.md** files
2. Generate **html** files in _site folder: `jekyll build` 
3. Update the **github pages**: 
   1. `git commit -am [notes]` 
   2. `git push`



## Clean up

Use `jekyll clean`



## Preview

Use `jekyll s`

Then go to `http://127.0.0.1:4000/` in any browser

If `Error:  Address already in use`, try:

 	1. ` ps aux | grep jekyll`
 	2. `kill [PID]` for the process `jekyll serve -B`

