# ECE444_Lab1

### Activity 5
Below is the screenshot of the commits (ie. c1, c2) I added to the branch called "rebase"
![rebase log](https://user-images.githubusercontent.com/42427479/133836360-3325a669-7856-4aae-ac41-2b0a0eef6e83.png)

The two commits I added to the **rebase** branch are commit 19dd0c9a96e6e47552614d14cbc916d4a34523b6 and commit 8235b7a949424465128728578d49b94ec8449a52.

After adding the two commits specified above, I also added two commits (ie. c3, c4) to the **develop** branch. 
![develop log](https://user-images.githubusercontent.com/42427479/133836910-50985adf-0e58-4609-8b28-af9a2407af77.png)

The two commits are commit 52e79e53ff4ffb94778a9711d72eee89a7bd3c83 and commit 814eab04f5646b6f2a6782ef70fcfb1c4db1b6ec.

Then, I go to the **develop** branch to apply a rebase for rebase branch. The commits are in the order of c2, c1, c4, c3 as shown below.  
![rebase screenshot](https://user-images.githubusercontent.com/42427479/133836158-578fd548-0946-456b-9c3c-5aff0ecf8327.png)

The approach I used to do rebase is 
```
git rebase -i rebase
```

The rebase process is shown as below
![screenshot of rebase](https://user-images.githubusercontent.com/42427479/133837570-b471b722-dc3f-4754-9ea4-623f55070eb6.png)


Note: I modified one of the existing file while adding c3, c4 commits, so the commit 814eab04f5646b6f2a6782ef70fcfb1c4db1b6ec is for resolving merge conflicts.
