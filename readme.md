## Installation and usage

    sudo npm install -g archey

The command is called `archeyjs` to avoid conflicts with the actual `archey` command.

## Examples

Note that the actual output has colors as well.

Ubuntu:

    [archey.js @master] archeyjs
                                .oyhhs:   User: m
                       ..--.., shhhhhh-   Hostname: precise64
                     -+++++++++`:yyhhyo`  OS: Ubuntu 12.04 x64
                .--  -++++++++/-.-::-`    Kernel: 3.8.0-29-generic
              .::::-   :-----:/+++/++/.   Uptime: 1 day 19 hours 30 minutes 59 seconds
             -:::::-.          .:++++++:  Shell: zsh
        ,,, .:::::-`             .++++++- Terminal: screen
      ./+++/-`-::-                ./////: Packages: 1266
      +++++++ .::-                        CPU: Intel(R) Core(TM) i7-3635QM CPU @ 2.40GHz
      ./+++/-`-::-                :yyyyyo Resolution: 3760x1920
        ``` `-::::-`             :yhhhhh: RAM: 3.69GB / 3.86GB
             -:::::-.         `-ohhhhhh+  Disk: 7.4G / 9.2G
              .::::-` -o+///+oyhhyyyhy:
               `.--  /yhhhhhhhy+,....
                     /hhhhhhhhh-.-:::;
                     `.:://::- -:::::;
                               `.-:-'

OS X:

    [m-mbp ~] archeyjs
                    :++++.         User: m
                   /+++/.          Hostname: m-mbp
           .:-::- .+/:-``.::-      OS: OS X 10.8.5 12F45 x64
        .:/++++++/::::/++++++/:`   Kernel: 12.5.0
      .:///////////////////////:`  Uptime: 12 days 7 hours 32 minutes 59 seconds
      ////////////////////////`    Window Manager: Quartz Compositor
     -+++++++++++++++++++++++`     Shell: zsh
     /++++++++++++++++++++++/      Terminal: screen
     /sssssssssssssssssssssss.     Packages: 10
     :ssssssssssssssssssssssss-    CPU: MacBookPro10,1
      osssssssssssssssssssssssso/` Resolution: 1200x1920, 2560x1440
      `syyyyyyyyyyyyyyyyyyyyyyyy+` RAM: 7.83gb / 8gb
       `ossssssssssssssssssssss/   Disk: 40G / 210G
         :ooooooooooooooooooo+.
          `:+oo+/:-..-:/+o+/-


Also includes logos for Arch Linux, CrunchBang, Debian, Fedora, Mint and Windows.

Options:

    --logo <name>   Display the logo for a specific distribution.
    --gallery       Display all the logos.
    --help          Show help.
    --version       Show version.

## Credits

Based on Archey by Melik Manukyan and screenfetch by Brett Bohnenkamper. The Archey and screenfetch credits mention the following people, so I want to acknowledge them here as well:

- ASCII art by Brett Bohnenkamper
- Changes by Jerome Launay
- Fedora support by YeOK
- OS X proting by shrx and Hu6

I figured I'd better not include their email addresses here given that this is a separate project.
