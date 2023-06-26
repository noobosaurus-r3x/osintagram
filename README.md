# osintgram

Osintgram is a Python script inspired by Palenath's [Toutatis](https://github.com/megadose/toutatis) script. 

I worked by adding a few options and rewriting his code. It is obviously not perfect but I thought it would be cool to share it anyway.

That script allows you to retrieve information about an Instagram user, including their profile details, profile picture, followers, and people following. Additionally, it provides options to save the output to a file and includes enhancements such as progress indicators, interactive prompts, and colored output.

## Features

- Retrieve user information including username, full name, verification status, follower count, following count, number of posts, biography, website, and more.
- Retrieve recent posts and their URLs and captions.
- Retrieve followers and their usernames and full names.
- Retrieve following accounts and their usernames and full names.
- Retrieve profile picture.
- Save the output to a file.
- Progress indicators for follower and following retrieval.
- Interactive prompts for follower and following retrieval.
- Colored output for improved readability and visual appeal.

## Requirements

- Python 3.x
- Requests argparse (`pip install argparse`)
- Requests library (`pip install requests`)
- Phonenumbers library (`pip install phonenumbers`)
- Pycountry library (`pip install pycountry`)
- Tabulate library (`pip install tabulate`)
- Tqdm library (`pip install tqdm`)
- Termcolor library (`pip install termcolor`)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/noobosaurus-r3x/osintgram.git
```
Navigate to the project directory:
```bash
cd osintgram
```
Run the script:
```bash
python osintgram.py -s <session_id> -u <username> [-f] [-g] [-o <output_file>]
```
or Interactive mode:
```bash
python osintgram.py -i
```
Replace <session_id> with your Instagram session ID and < username > with the Instagram username you want to retrieve information for.

To get your session ID, log into your Instagram account, and check your cookies. Copy/Paste the Value of the "sessionid".

Optional arguments:

-i, --interactive: Will ask you the necessary infos to run the script. Don't use any other argument with -i. 

-f, --followers: Retrieve and display followers.

-g, --following: Retrieve and display following.

-o <output_file>, --output <output_file>: Save the output to the specified file.

View the output in the console or check the saved output file, if specified.

# Credits
Osintgram is inspired by Palenath's Toutatis script. Special thanks to Palenath for the original creation. https://github.com/megadose/toutatis
