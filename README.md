# hello-world
Encountered my first PYTHON bug while learning PYTHON. This seemed to be a thing to do to at this point.
I am a Systems Engineer who started out mostly as a Test Engineer. I used a variation of the FORTH language to create my first automated test system for Baxter Travenol's CS3000 Blood Cell Seperator. After Baxter consolidated to corporate headquarters I used a version of FORTH to create an high speed test system front end for an EW Receiver.

Layoffs started in defense so I moved from Litton to Ohmeda and created a test lab for neonatal incubators using a version of FORTH called ASYST. After work dried up there I moved to FUSION Lighting and created an automated test system for electrodless microwave lighting devices using Visual Basic. These VB based systems were not as robust due to the system using networked computers that were constantly changing.

I had been sending Litton environment lab, failure analysis and test fixture construction work from Ohmeda and Fusion Lighting. When the layoff came to Fusion Lighting I went back to Litton and ended up working as their Software Configuration manager in order to make systems more robust. While I was there the received an SEI CMM II rating. JHU APL then statched me up so they could also get this same rating which I helped them attain.

After leaving FORTH software was very cumbersome for me to learn since I really didn't have any projects. Configuration Management challenges also became less rewarding as large projects attempted to use agile processes leaving the configuration manager out more and more. The good old CM tools got extremly buggy as competition drained their development base. I was pretty isolated from software development efforts while at DoS, but occaisionally got to peek at some projects. In the Pentagon I saw some software efforts from an even greater distance.

Maybe learing PYTHON will expose me to some recent software technology and will stick enough to make me as productive as FORTH did. It reminds me of ASYST. I was a little sad when I had to run a loop twice to get a job done for no apparent reason:

print("My sollution for problem in Head First PYTHON book that seems to demonstrate a PYTHON bug")
phrase = "don't panic!"
plist = list(phrase)
print(phrase)
print(plist)
ontap = [ 'o', 'n', 't', 'p' ]
for letter in plist:
    if letter not in ontap:
        plist.remove(letter)
        print(letter)
        print(plist)
print("For some reason I had to run the loop again to get rid of the \"c\"")
for letter in plist:
    if letter not in ontap:
        plist.remove(letter)
        print(letter)
        print(plist)
plist.insert( 2, ' ' )
plist.insert( 4, 'a' )
plist.pop()
new_phrase = ''.join(plist)
print(plist)
print(new_phrase)
