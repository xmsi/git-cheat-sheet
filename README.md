# What is github reabse

### From [Philomatics](https://www.youtube.com/watch?v=xN1-2p06Urc) youtube channel


## Normal Pull request (messy history)
![image](https://github.com/xmsi/github_rebase/assets/59314275/bf572d20-8dc0-405e-8d26-61383a2bbe79)


## Reabse version (clear history)
![image](https://github.com/xmsi/github_rebase/assets/59314275/6534382b-bde0-454e-8f94-b4fb72e069e6)

## all needed commands 
![image](https://github.com/xmsi/github_rebase/assets/59314275/cdebc075-f85d-4d45-861c-18087632b1b7)


- you can configure git pull so that it will always rebase by default. I was a bit wary of recommending this to people, since it changes the default behavior of a pretty common command, which might cause confusion (especially if you forget about it a few months later). If you want to make pull rebase the default, run `git config --global pull.rebase true`. From then on, `git pull` will rebase, and `git pull --merge` will merge.
In newer versions of git, it will even ask you upon first use which pull strategy you prefer.

- Use interactive rebase instead abort
