# dialogflow-teambuilding-agent

Dette er et team-building spill som går ut på samarbeid. Oppgaven krever systematisk kartlegging 
av informasjon og fokus på detaljer. Spillet er en krimgåte med 4 mistenkte som kan intervjues gjennom
en chatbot-agent. Man har oppgitt spørsmål man kan bruke til å utspørre de mistenkte, og mulighetern
til å avdekke skjult informasjon ved åstille de riktige spørsmålene.


Denne aktiviteten kan blir hostet på en pc, og dermed spilt gjennom en nettleser.
For å starte opp spillet starter man skriptet webpage.py

$ python webpage.py

Dette vil hoste en lokal nettside på pc'en din. Deretter starter man ngrok.exe, og eksponerer nettsiden til internett:

$ ngrok http 5000

Linken du får oppgitt brukes til å komme inn på spillet.