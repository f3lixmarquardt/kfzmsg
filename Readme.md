# KfzMsg

## Projektbeschreibung

MyProject ist eine Plattform, die es Autofahrern ermöglicht, basierend auf dem Kennzeichen des Fahrzeugs Nachrichten auszutauschen. Das Projekt verwendet eine Microservices-Architektur, um Skalierbarkeit und Flexibilität zu gewährleisten.

## Funktionen

- **Benutzerregistrierung und -authentifizierung**: Benutzer können sich registrieren und sicher einloggen.
- **Kennzeichen-Management**: Verwaltung von Kennzeichen als Themen für die Kommunikation.
- **Post-Erstellung**: Benutzer können Nachrichten zu bestimmten Kennzeichen posten.
- **Abonnement von Kennzeichen**: Benutzer können Kennzeichen abonnieren, um Benachrichtigungen zu erhalten.
- **Benachrichtigungssystem**: Sende Benachrichtigungen an Benutzer, wenn neue Posts zu abonnierten Kennzeichen erscheinen.

## Verzeichnisstruktur

```plaintext
my_project/
├── auth-service/
│   ├── src/
│   ├── tests/
│   ├── requirements.txt
│   ├── package.json
├── user-service/
│   ├── src/
│   ├── tests/
│   ├── requirements.txt
│   ├── package.json
├── post-service/
│   ├── src/
│   ├── tests/
│   ├── requirements.txt
│   ├── package.json
├── notification-service/
│   ├── src/
│   ├── tests/
│   ├── requirements.txt
│   ├── package.json
├── gateway-service/
│   ├── nginx.conf
│   ├── src/
│   ├── tests/
│   ├── requirements.txt
│   ├── package.json
├── .gitignore
├── README.md
