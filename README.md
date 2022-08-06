# Vesion-Control-Test
 Can I commit an entire Unity project to Git?!

Answer: Oh myy yes.

## Prerequisites

1. Install Unity3D.
2. Create a Github account.
3. Install Github Desktop (For Windows).
4. Sign into Github for Desktop.
5. Click File > Clone repository and search for `mercygamejam/Vesion-Control-Test`. (Or in Github click the green "Code" button and then click "Open in Github Desktop").
6. Open Unity Hub and click the "Open" button and select the `Vesion-Control-Test` folder. This should add it to the Unity Hub project list and open it in Unity Editor.

## Contribution Guide
1. Open Github Desktop.
2. Click the "current repository" tab and select `Vesion-Control-Test`.
3. Click the "current branch" tab and click the "new branch" button. Name it and click "create branch".
4. Open Unity Editor and make whatever changes you want, add scripts or models, move stuff around in a scene etc.
5. Save your changes.
6. The changes should appear on your branch in Github Desktop. **See note 1**.
7. If you don't like the changes you can always right click a file on the left sidebar and click "Discard changes". Then if Unity asks you to reload the scene click "Reload" in Unity Editor.
8. If you do like the changes and want to send them to Github, add a summary (title) and optional description in the lower left box and click commit to "name of your branch".
9. 

## Notes
1. Most things are just text files with data so changes should appear as line changes in green (addition) or red (deletion). If it's a 3D model or something it should add a "large file" which is ok since we're using Github Large File Storage (an extension for this purpose); It's still recommended to keep assets under 50-100MB each though. I think the entire project can go up to 100GB but I doubt we'll even reach 2GB, because that's like the size of a small console game.
2. To avoid conflicts where two people are changing the same scene and merging commits, it's best to click "Fetch origin" before starting a new branch or opening a pull request to make sure you're not trying to overwrite something that's changed while you were working on your branch.
3. When you open the project with Unity Hub, Unity will create a a lot of Library files and other folders and stuff that aren't necessary to share, because they can be built automatically on each person's computer. The files are very big and nasty so it's best to keep them out of Github anyways. Git knows to ignore them because the files and folders to ignore are listed in the `.gitignore` file; this shouldn't be changed unless another exception is found.
