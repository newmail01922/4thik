Local setup instructions:

1. Install Hugo version v0.54.0 for the site to render properly
1. clone hugo learn theme from https://github.com/matcornic/hugo-theme-learn, update `themesdir` in config.toml
1. `cd python` then, `hugo server -D` to run local server

Note: the file and folder names don't contribute to order, and may not always be accurate. Sorted by chapter and individual page weight.

If you move things around or delete chapters, you may have to restart the server for the chapters to appear correctly.

How to use the theme: https://learn.netlify.com/en/cont/
More about theme shortcodes: https://learn.netlify.com/en/shortcodes/

use `git lfs` for tracking binary types.
# To take input from the user
#num = int(input("Enter a number: "))

# define a flag variable
flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

    # check if flag is True
    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")# To take input from the user
#num = int(input("Enter a number: "))

# define a flag variable
flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

    # check if flag is True
    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")

```bash
$ git lfs track "*.psd"
git add .gitattributes
```

Currently tracked types:
 - .png
 - .jpg
 - .jpeg
 - .pdf
 - .mp4
 - .gif
