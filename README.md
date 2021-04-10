# petname-system
a system that attempts to  decentralize names without blockchain or dns.
several white papers exist about the concept.

this project attempts to add browser extensions that implement the protocol on standard browser.



http://www.skyhunter.com/marcs/petnames/IntroPetNames.html\
http://www.researchgate.net/publication/221426438_Security_Usability_of_Petname_Systems


a simple overview of the concept
in the current system of the web  exists dns which attempts to beat zookoo's triangle.

![zookoo triangle:global,securely unique,human-memorable](http://www.skyhunter.com/marcs/petnames/zooko-triangle.gif)

the problem with dns is  it centralized allowing for things like squatting, and censorship to exist.
the petname system attempts to solve zooko's triangle and dns issues.
instead of a single name for entities the systems uses 3 different names with unique security properities.
* keys - global and securely unique. many times the hash of a public key these keys are very hard to remember.
* nicknames/suggested names for various entities. - extremely forgable and mimicable.(entirely optional for a site).
  * 
* petnames, a unique name stored entirely locally that you can remeber.
    * they represent the key locally on this computer.

security issues with petnames

transfer of keys to users with trust
how do you know google is the google your friends. suggested it? 
using web of trust ideas, the friend uses a signed referral if not over  a secure channel.
this can be done automatically - with hidden ui  showing security of key(who trusts it?)

non signed refferal ideas!!!
  - lookup similar nickname with small security details including
  - number of(personal)  trusted  signers used, untrusted signatures.
  - organazition signatures(ie. goverment bodies).

nicknames to petnames
when helping users to convert nicknames to petnames, 
i suggest that a  petname include a few bytes or characters of the key


