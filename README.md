
# TriathlonForge
=======
1. Aplikacija za trialton
SVRHA APLIKACIJE:TriathlonForge je aplikacija za trkače i triatlonce koja omogućava praćenje i analizu fizičkih aktivnosti koristeći podatke sa STRAVA ili Garmin profila. Cilj je unapređenje treninga kroz detaljne analize i personalizovane preporuke.


1. Login
2. Register
3. Home Page
4. Pace Calculator  Bmi Calculator calculatori su na istoj stran 
5. Profile Page
6. Calendar Page 
7. Chat Page 


1. cemu aplikacija sluzi
3. Kome je aplikacija namenjena
4. Kako se unose podaci
    1. Kako se obrađuju podaci
5. Koi su rezultati obrade podataka
6. Da li se podaci dele
7. Da li se prave profili korisnika


1. Otvoriti aplikaciju
2. Ulogovati se sa STRAVA nalogom, proverava se presto API ja da li se poklapaju kredencijali sa STRAVI-nom bazom
3. Posle uspešnog logovanja učitava se stranica sa STRAVA naloga koja prikazuje sve aktivnosti korisnika
4. Korisnik odabere aktivnost i učitaju mu se informacije o - distanci, -prosečnom pejsu, -vremenu trajanja aktivnosti, - potrošenim kalorijama, prosečni otkucaji srca
5. Ispod toga ima dogme

Svaki user se registruje I pre tome unosi svoj link ka profilu sa Strave ili Garmin (odlucicu se Kad krenem da pravim aplikaciju)
1. za aplikaciju treba da ima login, register, homepage, pace calculator, bmi calculator, profile page gde se vidi napredak 
2. preko grafika koji pokazuje pace za trčanje, speed na bajsu sve to na mesečnom nivou

2. Home da prikazuje aktivnosti ulogovanog korisnika samo sa textom od podataka koje api skuplja podatke sa gore navedenih izvora

3. Pace calculator se pravi po ovim formulama  	
* time = pace × distance
	time = pace time per unit distance × distance
* distance = time / pacedistance = time / pace time per unit distance
* pace = time / distancepace time per unit distance = time / distance
* speed = distance / time
4. Aplikacija treba da generiše, na osnovu podataka iz Strave ili Garmina: mesečne izveštaje o aktivnostima (pređenja distanca, da li je korisnik usporavo ili ubrzavao na mesečnom nivou, mesečne varijacije u pulsu, pace-u, kadenci, kalendar aktivnosti)
5. Godišnje izveštaje o napretku!
6. Predloge za nove aktivnosti, recovery
7. Na profile page treba da ima Ime korisnika Prezime, godište i da prikažu prosečan hr tokom aktivnosti broj aktivnosti
8. Napraviti mogućnost da se dadaju plan treninga i salju notifikacije kad treba da se odradi
9. Mogućnost deljenja aktivnosti na društvene mreže 
10. Kalendar gde je moguce upisati aktivnost
11. Prilikom upisivanja aktivnosti odabrati tip aktivnosti
12. Poslati notifikaciju dan pred aktivnost i ispisati ime i tip aktivnosti
13. Koristimo Strava Api jer je besplatan i može da se koristi za logovanje na aplikaciju
