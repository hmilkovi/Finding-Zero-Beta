# ! Warning, this document contains spoilers!

This document contains work for an Open-source intelligence (OSINT) assignment. The assignment is fictional, the target is not a real person.

# Assignment  
In a cyber crime case, a suspect with the e-mail address z3r0b3t404@gmail.com has been identified. Using OSINT, can you find the first and last name of the suspect?

# Possible handles
## User names
Using the given e-mail address z3r0b3t404@gmail.com, we assume z3r0b3t404 as a possible user name.

## E-mail addresses
Extrapolating the user name using popular e-mail domains, we get a list of the following additional e-mail addresses:
1.	z3r0b3t404@aol.com
3.	z3r0b3t404@gmx.com
4.	z3r0b3t404@googlemail.com
5.	z3r0b3t404@hotmail.com
6.	z3r0b3t404@hotmail.co.uk
7.	z3r0b3t404@live.com
8.	z3r0b3t404@outlook.com
9.	z3r0b3t404@mail.com
10.	z3r0b3t404@msn.com
11.	z3r0b3t404@yahoo.com
12.	z3r0b3t404@yahoo.co.uk
13.	z3r0b3t404@yandex.com

E-mail verification via [Verifalia](https://verifalia.com/validate-email) shows three e-mail addresses are valid: 
1.	z3r0b3t404@gmail.com
2.	z3r0b3t404@googlemail.com
3.	z3r0b3t404@hotmail.com

# Findings
## Clear web
### Search engines
1.	Google
2.	Bing
3.	Yandex
4.	DuckDuckGo

All search engines show no relevant pages when looking searching directly for the possible user names and e-mail addresses.

### Online user accounts
To search user accounts online, several tools have been used.
1. Spiderfoot
2. Skiptracer
3. OSINT-SPY

The following user accounts were found:
1. [Destructoid.com](https://www.destructoid.com/?name=z3r0b3t404&a=454331&start=0&chaos=ok)
   * No publicly available ties to other accounts.
   * No publicly available content (posts, following).
   * Creation at 4:21 PM on May 24, 2019

## Deep web:
1. Google
   * “Zero Beta” shows up as the name in Google Hangouts, under the gmail e-mail address.
2. Facebook
   * Facebook accounts linked to the gmail and googlemail e-mail adresses have been disabled.
   * Note: The account recovery page, when inputting: z3r0b3t404@(X)mail.com always give a hit, so: mail.com, dmail.com, kmail.com, gmail.com. Bug? Does this mean (g)mail.com is a false positive?
3. LinkedIn
   * LinkedIn account is present under the gmail e-mail address.

## Data breaches
The user names and e-mail addresses have not been found in any data breaches according to [haveibeenpwned.com](https://haveibeenpwned.com/)

# Oberservations
1. The name "Zero Beta" tied to z3r0b3t403@gmail.com is a pseudonym which explains that the e-mail address is written in [“leetspeak”](https://en.wikipedia.org/wiki/Leet), in which it can be read as:  ZeroBeta04@gmail.com.
   * The e-mail address z3r0b3t403@gmail.com has been verified to not exist.
   * Zero Beta could have a meaning. Beta can refer to the second letter of the Greek alphabet, or the numeric value 2. Together making: “0B04” or “0204”.
2. E-mail addresses shows little on search engines and have not been compromised by data breaches. This suggests that the e-mail addresses have not been used much and/or for long, and are possibly burner accounts. The creation date of the account on destructoid.com aligns with the possibility that it is a new e-mail address.

# Findings #2

When we search for zerobeta04 on google we find a website under the domain zerobeta04.nl
The homepage of the website states in Dutch that it is under construction.
Crawling the webserver gives us the page /notes.txt, which contains the following text:

>Marktplaats:

>Boggle - moet nog

>Blackberry - https://www.marktplaats.nl/a/telecommunicatie/mobiele-telefoons-blackberry/m1451348153-pgp-blackberry.html

It looks like the website owner created a to do list, stating he/she wants to sell some items on marktplaats.

## The marktplaats listing #1
The listing is of a PGP Blackberry created at 30th of August 2019 @ 13:50.
The description of the listing shows the following text:
>Beschrijving

>Meerdere PGP-telefoons aangeboden.

>Merk BlackBerry. Verzending heel Nederland.

>Check ook mn andere advertenties (hohner starlet enz.)

>Moet overal van af.

The listing provides the following images:

![p1](images/marktplaats-1/1.jpg)
![p2](images/marktplaats-1/2.jpg)
![p3](images/marktplaats-1/3.jpg)

The location of the advertisement is set to Stitswerd, Groningen.

The stated city, according to Wikipedia has a population of about 50 inhabitants and uses the postal code 9999. This indicates that the set location is a fluke.

The listing is created by the user **JG_zerobeta04**, who has been active on the website since May 2019.
The account does not have other listings, which is what we would not assume from the above description of the listing.

## The marktplaats listing #2
When we search Marktplaats for "hohner starlet", we get the following [listing](https://www.marktplaats.nl/a/muziek-en-instrumenten/accordeons/m1451345767-accordeon-hohner-starlet.html?c=08c285449651fa109c354bbabe740c1b&previousPage=lr)

The listing is of an accordion, created at 30th of August 2019 @ 13:44.
The description of the listing shows the following text:
>Accordeon Hohner Starlet 40

The listing provides the following images:

![p1](images/marktplaats-2/1.jpg)
![p2](images/marktplaats-2/2.jpg)
![p3](images/marktplaats-2/3.jpg)
![p4](images/marktplaats-2/4.jpg)

The location of the listing is set to Almere, Flevoland.

The advertisement is created by the user **jiuseppegrande**, who has been active on the website since May 2019. This coincides with the creation date of the other marktplaats account.
The account also does not have other listings.

## Twitter account
From the username jiuseppegrande we can find a [twitter account](https://twitter.com/jiuseppe_grande)
The twitter account was created on April 2019 and follows all kinds of cyber security accounts.

Profile picture:

![Profile picture](images/twitter/profile-picture.jpg)

A tweet posted by the account reads the following:

![Boggle](images/twitter/boggle.jpg)
>Iemand voor een potje boggle? anders gaat ie op marktplaats.

The author asks if anyone wants to play Boggle the word game with him, and says if he doesn't find anyone he will put it up on Marktplaats.

## Ello account
A [reverse image search](https://www.reverseimagesearch.com/) using his profile picture gives the following account of a [Josh Grootegast](https://ello.co/joshgrootegast) living in **Almere, Flevoland**.

The account has a post which reads as follows:

![Boggle](images/ello/boggle.jpg)
>Heb niemand gevonden om Boggle mee te spelen dus deze kan verkocht worden. Geïnteresseerde kopers kunnen mij bereiken via: z3r0.b3t4.04 AT gmail.com

Stating he has been unable to find someone to play Boggle with and therefore is selling it, and that he can be contacted at z3r0b3t404@gmail.com, **confirming that Josh Grootegast is z3r0b3t404@gmail.com**.
