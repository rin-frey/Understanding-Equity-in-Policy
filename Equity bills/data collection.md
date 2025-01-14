Search and Collection Process:

-   Utilized a Boolean search on the Govinfo.gov database to identify
    equity-related bills from the 117th Congressional session, focusing
    on House bills
    [search
    term](https://www.govinfo.gov/app/search/%7B%22query%22%3A%22equity%20OR%20marginalized%20OR%20barriers%20OR%20wage%20equity%20OR%20income%20inequality%20OR%20gender%20equity%20OR%20climate%20justice%20OR%20health%20OR%20disability%20rights%20OR%20school%20readiness%20OR%20BIPOC%20OR%20underserved%20OR%20Medicaid%20OR%20diversity%20OR%20inclusion%20OR%20disadvantage%20OR%20systemic%20inequality%20OR%20justice%20OR%20financial%20literacy%20OR%20healthcare%20access%22%2C%22offset%22%3A0%2C%22facets%22%3A%7B%22publishdatehier%22%3A%5B%222024%22%5D%2C%22accodenav%22%3A%5B%22BILLS%22%5D%2C%22governmentauthornav%22%3A%5B%22Congress%22%5D%2C%22dochierarchy%22%3A%5B%22House%20Bill%20(H.R.)%22%5D%7D%2C%22filterOrder%22%3A%5B%22publishdatehier%22%2C%22accodenav%22%2C%22governmentauthornav%22%2C%22dochierarchy%22%5D%7D)

-  #### Boolean Search

> equity OR marginalized OR barriers OR wage equity OR income inequality
> OR gender equity OR climate justice OR health OR disability rights OR
> school readiness OR BIPOC OR under-served OR Medicaid OR diversity OR
> inclusion OR disadvantage OR systemic inequality OR justice OR
> financial literacy OR healthcare access

This is not a comprehensive search term, but looked to encompass as much
as possible while staying inside the search parameters on govinfo.

These equity bills were then downloaded into a csv, that included
relevant bill title, dates, co-sponsors..etc In order to collect the
bill text, the htmls links needed to be systematically opened,
webscraped and downloaded into a csv with their relevant titles. In
order to do this efficiently, I used colab and gemini to develop a
script for this, leaning on the methodology given by [Erik
L](https://medium.com/@lobodemonte/congress-gov-web-scraping-with-beautifulsoup-37af19f2e1f4).
The link to the colab script:\
[Colab
Notebook](https://colab.research.google.com/drive/1XAZ_AMdDEgsSw-s4D6sB5tvxFZrkY4IF?authuser=0#scrollTo=51aUtRCPAN3E).

(colab script also in this repo)
