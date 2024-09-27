# Easy-hosting-llm-jailbreaking


```
git clone https://github.com/dhammon/ai-goat
cd ai-goat
docker compose up -d
```
then 

```
./ai-goat.py --run 1
```

You can change the flags within the challenges source code and then in CFTD (they must match).

After you clone the repo, navigate to ai-goat/app/challenges/1/app.py and change the flag in the string on line 12.
Then navigate to ai-goat/app/challenges/2/entrypoint.sh and change the flag on line 3.
Next you will need to change the flags in CFTD. Launch CFTD and then login with the root user using qVLv27Dsy5WuXRubjfII as the password.
Once logged in, navigate the admin panel (top nav bar) -> Challenges (top nav bar) -> select a challenge -> and hit the Flags sub-tab.
Change the flag for each CFTD challenge to match the same string you changed the in the source code.
Have fun!
