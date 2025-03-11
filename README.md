# 1. Disclaimer
**If you are not within my friend group, you probably shouldn't care about this repo**

# 2. Dependencies
## (Optional)
(Optional) Install pyenv for python version management `https://github.com/pyenv/pyenv`

Install python using pyenv and make it local to this project

Create virtual environment
```
python3 -m venv .venv
source .venv/bin/activate
```

## Install dependencies
`pip install -r requirements.txt`

# 3. Credentials
You will need an account with Google Sheets API and Google Slides API access enabled and OAuth2 configured. Alternatively, become my friend and get the `credentials.json` from me :))

# 4. How to run
`python main.py -h` should give you all the options

If you are still clueless, the command should look something like `python main.py -n ndtt_test -u urls.csv -d 30 -f 4`

Note:
1. Excel sheet should be reused from previous seasons
2. `urls.csv` file should have 2 columns, first column is url for the songs, and second column is name of player. Template is attached
3. Duration is not required, you should listen on your own
4. Filler should be greater than 0 (this is a bug from Long, contact him for fix)
5. A new csv file called `shuffle_music.csv` will be created, copy and paste this to the result Excel sheet

Upon first launch/whenever credentials expire, a browser tab will open up and ask you to sign in into your Google account. Give all the permissions asked. Remember the account I mentioned above? Use it, especially if you don't want to use your main account.
