# jump-dev-badges
TeX file used to generate badges for JuMP-dev 2019. The `badge-JuMP-dev-7x8.tex` files has the final version used for the badges (we used a size of 63mm x 82.5mm).

## Usage
* Modify the `ticketdefault` command for changing the text and logo that is common to all badges.
* Modify the `cofpin` command to organize the information particular to each attendee.
* You can generate multiple badges by calling, in the document body, the command `confpin` with the information of each attendee.

## LaTeX Requirements
* The `ticket` package (<https://ctan.org/pkg/ticket?lang=en>).
* The `memoir` package.
* The `qrcode` package.
