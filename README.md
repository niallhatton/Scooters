# Zoom E-Scooter Fleet Management

This project was created for the development of a new business in the UK

## Contributing
This is a private project

## Graphics
The logo graphics were designed custom for this project using the 
website www.designcrowd.com. This includes the logo and, iphone/ipad icon and favicon.

I own full rights to these graphics.

The hero image was a stock photo I purchased for this project from Adobe Stock.

## CSS Tricks
Nav Bar Underline
I used a trick found on w3schools to put a border on the bottom of a div to give an underline affect. I then used this with the active link css rule to apply a underline to nav bar item to show
which page you were currently on.
https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_navbar_border

Collapsible list
To get the collapsible list on the about us page I researched various techniques some used JavaScript and jQuery however these introduced problems into the site which I deemed more effort to fix
than the value added. I ended removing these and opting for a pure CSS solution which I customised slightly to get the effect I was looking for. The orginal code is found below on Digital Ocean.
https://www.digitalocean.com/community/tutorials/css-collapsible

## Challenges
Comparison to the wireframes will show that I deviated from the sketches slightly with the content in each section. This is due to a delay in the launch of the business.
Orginally I had planned to already be running the business by the time this project was completed, however due to delays outside my control the launch has not taken place.
This caused issues as I was unable to have the cities confirmed and statistics such as number of scooters in each area to hand, model of scooters deployed etc. This meant having a
section dedicated to statistics did not make sense. I did consider using "fake" statistics but decided against that due to wanting to launch the site without much/any changes to the 
site when that time comes.

## Hosting/Domain
The domain www.zoomscooter.co.uk was purchased for this project using gandi.net, DNS records are also configured here.
The site is hosted in Azure cloud on a custom VM I manage. DNS records in Gandi are pointing to the Azure VM.

The Azure VM is running Centos 7 with Webmin/Virtualmin for hosting software custom installed. Webmin allows for a GUI to easily create multiple hosting for each site.
https://virtualmin.com/ - Open Source Web Hosting and Cloud Control Panels.

A sub domain dev.zoomscooter.co.uk was used as 
a staging site with the main domain hosting a holding page while development was taken place.

## Gitpod Testing

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

## Credits
I had some advice from the Slack group and used Love Running project as a template and guide for my design
