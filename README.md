# Tutorial-Risc-Zero-Node

minimum spec: 8GB RAM

Web : https://www.risczero.com/

1️⃣ Install the dependency and binary
curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | sh -
source ~/.profile
mkdir p0tion-tmp
cd p0tion-tmp
nvm install 16.20
nvm use 16.20
npm install @p0tion/phase2cli


📌 If there is an error at the end, install the cargo first
cargo install cargo-binstall
cargo binstall cargo-risczero
cargo risczero install

Re-enter the install dependency command at the beginning again until you get to the banner

2️⃣ Have a github account minimum requirements
- Followers 5
- Followers 5
- Create 5 Public repositories

3️⃣ Github account authentication
npx phase2cli auth
- click the login link at the top of the banner enter the generated code until the terminated github username appears

4️⃣ Contribute
- Create a new screen
screen -RS risczero
- Enter the command
npx phase2cli contribute

**If successful, it will appear like this
You must wait for contributor xxx (~xx:xx:xx:00 (dd/hh/mm/ss))

Exit the screen: CTRL+A+D
Enter screen again screen -r risczero

Details: https://www.risczero.com/blog/ceremony-contribution-public-instructions
Tutorial: https://p0tion.super.site/ce8f7047468b41239dc512919644535c

Translated with DeepL.com (free version)
