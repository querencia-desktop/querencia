# Querencia Desktop – Meldungen

Querencia Desktop ist eine klassische Desktopumgebung im Stil von GNOME 2 für
Wayland (labwc, Rust, GTK 4), zurzeit als Alpha 3.3 für Ubuntu 26.04. Alles
Weitere auf <https://querencialinux.org>.

*Querencia Desktop is a classic GNOME-2-style desktop for Wayland (labwc,
Rust, GTK 4), currently Alpha 3.3 for Ubuntu 26.04; everything else is on
<https://querencialinux.org>.*

[Deutsch](#deutsch) · [English](#english)

## Deutsch

Fehler, Wünsche und Fragen zu allen Programmen von Querencia Desktop. Wer
nicht weiß, welches Paket betroffen ist, meldet trotzdem hier.

### Melden

[Neue Meldung](https://github.com/querencia-desktop/querencia/issues/new/choose),
dann „Fehler melden“, „Wunsch“ oder „Frage“ wählen. Vorher
[suchen](https://github.com/querencia-desktop/querencia/issues?q=is%3Aissue),
ob es die Meldung schon gibt. Deutsch oder Englisch.

### Beilegen

- `dpkg -l 'querencia-*' labwc`
- `lsb_release -ds`
- Schritte zum Nachstellen, erwartetes und tatsächliches Verhalten
- etwa 50 Zeilen aus dem passenden Log in `~/.local/state/querencia/`
  (Sitzungsstart: `sitzung-start.log`)

### Schwärzen

Meldungen sind öffentlich. Vor dem Absenden entfernen: Heimpfade,
Benutzer- und Rechnernamen, IP-Adressen, `smb://`-Adressen, private
Dateinamen. Das Log der Benachrichtigungen kann Nachrichtentexte enthalten.

### Sicherheitslücken

Nicht öffentlich melden, sondern über
[Report a vulnerability](https://github.com/querencia-desktop/querencia/security/advisories/new).

### Ablauf

Neue Meldungen werden nachgestellt, einer Komponente und Schwere (P0–P3)
zugeordnet und für eine Alpha eingeplant. Ist die Korrektur als Paket in
der APT-Quelle, steht das mit Version in der Meldung.

## English

Bugs, feature requests and questions for all Querencia Desktop programs.
If you do not know which package is affected, report here anyway.

### Reporting

[New issue](https://github.com/querencia-desktop/querencia/issues/new/choose),
then pick "Report a bug", "Feature request" or "Question".
[Search](https://github.com/querencia-desktop/querencia/issues?q=is%3Aissue)
first whether it has been reported. German or English.

### Include

- `dpkg -l 'querencia-*' labwc`
- `lsb_release -ds`
- steps to reproduce, expected and actual behaviour
- about 50 lines from the matching log in `~/.local/state/querencia/`
  (session start: `sitzung-start.log`)

### Redact

Reports are public. Before submitting, remove home paths, user and host
names, IP addresses, `smb://` addresses and private file names. The
notifications log may contain message texts.

### Security vulnerabilities

Do not report them publicly; use
[Report a vulnerability](https://github.com/querencia-desktop/querencia/security/advisories/new).

### Process

New reports are reproduced, assigned a component and severity (P0–P3) and
planned for an alpha. Once the fix is in a package in the APT repository,
the report says so with the version.

## Lizenz / Licence

CC BY-SA 4.0 ([LICENSE](LICENSE)), ausgenommen Name und Logo „Querencia“ /
except the name and logo "Querencia".
