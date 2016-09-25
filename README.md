# githook-explode
[githooks](https://git-scm.com/docs/githooks) - pre-receive: Script that gets excecuted when the server receives a push. Can be use to stop or accept new commits.
<img src="https://github.com/kikeonline/githook-explode/blob/master/githook-explode.png" width="600">

# Instalation
Copy the pre-receive script to .git/hooks probably you already have some example files there.

Give excecutable permissions.
  ```bash
  $sudo chmod +x pre-receive
  ```

I used this file as a base to make more complex tasks. In this particular script if the commit message that is being pushed has less than 50 characters the commit is not accepted and the terminal explodes.

Used it to fulfill your needs. Imagination is the limit ✌️
