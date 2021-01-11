# Trin 1: Kompatibel Computer

!!!danger "Tidsestimat"
    * 5 minutter, hvis der allerede er Mojave eller Catalina macOS
    * 30-60 minutter, hvis det er nødvendigt at installere macOS-opdateringer

!!!info "Resume"
    * Tjek din macOS og sørg for at den er Mojave eller Catalina. **Hvis du har den nyeste iOS-version på iPhonen, der vil bruge Loop... så har du brug for Catalina.**
    * Brug ikke nogen af beta- macOS-versionerne. (Hvis du ikke ved, hvad det betyder, så fortvivl ikke... det betyder, at du ikke bruger ét)
    * Hvis din macOS ikke er Mojave eller Catalina, skal du kontrollere, om du kan opdatere din macOS til en af dem.
    * Hvis du ikke kan opgradere din eksisterende computer til Mojave eller Catalina, skal du låne computer, Patcher værktøj, eller måske en ny / brugt computer kompatibel med Mojave eller Catalina.
    * Tjek `Softwareopdateringen` for at se, om din computer har opdateringer tilgængelige, siden du først installerede den.

!!!warning "FAQs"
    * **"Kan jeg bruge en pc eller Windows-computer? Jeg ejer ikke en Apple-computer."** Ja...sådan da Se venligst [denne FAQ om brug af Virtual Machine](https://loopkit.github.io/loopdocs/faqs/FAQs/#can-i-use-a-pc-or-windows-computer-to-build). Windows-computere med AMD-processorer vil ikke være i stand til at opbygge med succes ved hjælp af Virtual Machine, så sørg for at tjekke din processor type før du indleder Virtual Machine sti.
    * **"Hvad kan jeg gøre, hvis min computer er for gammel til at blive opgraderet til Catalina?** Du kan tage et kig på ved hjælp af [Catalina Patcher](http://dosdude1.com/catalina/), men dette er helt på egen hånd og ikke en del af disse instruktioner. Bare tilbyder svaret på FAQ... det er op til dig at læse om patcher værktøj og hvilke risici det kan indebære for dig.
    * **"Kan jeg låne en andens Apple-computer?"** Ja, se [dette FAQ om at låne en computer](https://loopkit.github.io/loopdocs/faqs/FAQs/#do-i-need-to-own-my-own-apple-computer) for at lære mere.
    * **"Hvor ofte skal jeg bruge computeren?** Computeradgang er kun påkrævet, når du i første omgang installerer Loop app eller opdaterer til en nyere Loop release. Du behøver IKKE adgang til en Apple-computer for at fejlfinde eller ændre Loop indstillinger, såsom basalrater eller kulhydratsforhold.

## Nye M1 chip Apple-computere

Ja, de nyeste Apple-computere, der netop blev udgivet i november 2020, er kompatible med Loop building. Der er ET lille skridt du skal være opmærksom på med de nye computere, og det er på Trin 7 Installer Homebrew side. Jeg har fremhævet i en farvet bokse på denne side de dele, som M1 brugere bliver nødt til at gøre. Jeg lover, det er hurtigt og smertefrit.

Og med det...Jeg er meget jaloux, at du har den nye computer. De vil gøre Loop bygning ekstremt hurtigt, og tidsestimaterne nævnt øverst vil være latterligt langsommere end du vil opleve.

## Big Sur MacOS

Ja, Big Sur er kompatibel med Loop building...Jeg arbejder på at opdatere denne side for det snart. Afvent.

## Catalina vs Mojave, hvilken har du brug for?

Har du brug for Catalina eller Mojave? Svaret vil afhænge af iOS på din iPhone, du vil installere Loop på.

**Hvis du har iOS 12.4 til 13.2**, kan du bruge macOS 10.14.4 (Mojave) eller 10.15.2 eller nyere (Catalina).

**Hvis du har iOS 13.4 eller nyere**, vil du ikke være i stand til at bruge Mojave og vil have brug for Catalina på et minimum. Med andre ord, du har brug for macOS 10.15.2 på et minimum for at bygge Loop på en iPhone, der kører iOS 13.4 eller nyere.

!!!danger "iOS dictates your computer needs" Put simply for Loopers...the more up-to-date you keep your iOS, the more up-to-date your computer and macOS will need to be, too. That's not necessarily a bad thing, and you can't avoid iOS updates forever...you just do need to be aware of how they relate to each other if your computer is "getting on the older side".

## Check your macOS
You need an Apple computer that has at least the minimum macOS version as described above; Mojave macOS 10.14.4 (or newer) or Catalina macOS 10.15 (or newer). To find out which version you have installed, click on the little Apple icon in your computer's upper left corner and select the `About this Mac`. It doesn't matter if the computer is a MacBook, iMac, macMini, etc...just so long as it has the minimum you'll need.

If your computer does not have the required minimum version, you'll need to check the `Software Update` button on that screen to see if you can update.

<p align="center">
<img src="https://loopkit.github.io/loopdocs/build/img/macosx.png" width="500">
</p>

If your computer does not give you the option to update to the newer macOS (in other words you are stuck on older versions)...it is quite possible that Apple has decided your computer is too old to run the latest and greatest. How old is too old? That will depend on your computer model and year as shown below:

<p align="center">
<img src="https://loopkit.github.io/loopdocs/build/img/mojave-minimum.png" width="750">
</p>

## Next Step: Compatible iPhone/iPod touch

Now you are ready to move onto Step 2 to check if you have a [Compatible iPhone/iPod touch](https://loopkit.github.io/loopdocs/build/step2/).
