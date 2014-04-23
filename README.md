# Sugar Activities

This contains all the data for ASLO activities

# Adding yours

First add this to the `activities` object in data.json:

    "YOUR_BUNDLE_ID": {
            "by": [
                {
                    "name": "YOUR_NAME", 
                    "page": "YOUR_SITE",
                    "email": "YOUR_EMAIL used to reply to peoples comments",
                }
            ], 
    }

Then send us a pull request. Someone will look at your activity.

# Hooking it up

You should then add a github web hook for your activity.
That means the bots will build and do stuff for you.
The webhook address is:

    http://WE_DON'T_HAVE_A_HOST_YET:5001/hook/GITHUB_USER/GITHUB_REPO/BUNDLE_ID

# Getting ready for the bots

* Make sure you have a setup.py
* Put your screenshots in `/screenshots/LANG/`. eg: `/screenshots/en/1.png`
* Add summary and title to activity.info
* Translate activity.info (if you can) using po files
