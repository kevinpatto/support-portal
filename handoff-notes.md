# Developer handoff notes

## What I delivered
index.html, styles.css, support-checklist.md. Added a customer requirement to include order number, as well as a FAQ list.

## How I verified the page
I used git status to check whether my changes were staged for commit. Then after committing, I used git push origin main to update the GitHub remote repository, and checked to see if all of my changes were done there.

## Remote change I received
Additional line on escalation, used git pull --ff-only origin main. In actuality, I just used my IDE to pull the changes because I'm not an insane person.

## Git workflow explanation
The command git commit does not update GitHub as it only commits staged changes to the local version of the branch.