---
layout: default
title: Anmeldung
---

# Dein erster Besuch beim CoderDojo Passau

**Eine Anmeldung ist nur erforderlich, wenn du noch nie beim CoderDojo warst. Hast du bereits einmal teilgenommen, kannst du ohne Anmeldung zu allen <a href="termine.html">Terminen</a> kommen.**

So läuft dein erster Besuch beim CoderDojo Passau ab:

1. Lies die Informationen durch, die wir für dich zusammengestellt haben.<br/>
   <a class="btn btn-material-light-blue-700" href="/infos/kinder.html" target="_blank">Infos für Coder&nbsp;...</a>&nbsp;

1. Lies gemeinsam mit deinen Eltern die Informationen durch, die wir für sie zusammengestellt haben.<br/>
   <a class="btn btn-material-light-blue-700" href="/infos/eltern.html" target="_blank">Infos für Eltern&nbsp;...</a>&nbsp;

1. Du füllst das <a href="#form">Anmeldeformular</a> unten aus.<br/>
   <a class="btn btn-material-light-blue-700" href="#form">Anmeldung&nbsp;...</a>&nbsp;

1. Wir schicken dir eine Email und bestätigen den Termin.

1. Du kommst mit <a href="/infos/eltern.html#Laptop" target="_blank">deinem Laptop</a> zum CoderDojo Passau in den <a href="#Wissensturm">Wissensturm</a>. Falls du keinen eigenen Laptop hast, gib im Anmeldeformular an, dass du ein Leihgerät brauchst.

1. Eine Mentorin oder ein Mentor vom CoderDojo Passau zeigt dir, wie das CoderDojo funktioniert und gibt dir Tipps, womit und wie du starten könntest.

## <a name="form" />Anmeldung

<div class="row registration-form">
  <div class="col-sm-10 col-md-8 col-lg-6">
    <div class="card card-block">
        <div class="registration-finished hide">
            <h3>Anmeldung abgeschlossen</h3>
            <p>Danke für deine Anmeldung, wir freuen uns schon auf dich!</p>
        </div>
        <div class="registration-error hide">
            <h3>Fehler bei der Anmeldung</h3>
            <p>Die Anmeldung ist leider fehlgeschlagen. Bitte kontaktiere uns unter <a href="mailto:info@coderdojo-linz.org">info@coderdojo-linz.org</a>.</p>
        </div>
        <form class="registration" id="registration-form">
            <h3>Ich möchte zum ersten Mal zum CoderDojo kommen</h3>
            <div class="form-group">
                <label for="event">Termin</label>
                <select id="event" class="form-control">
                </select>
                <div style="padding-top: 15px"><small><small>Der Ort kann sich in seltenen Fällen ändern. Bitte überprüfe einige Tage vor der Veranstaltung unter <a href="termine.html" target="_blank">Termine</a>, ob der Veranstaltungsort geändert wurde.</small></small></div>
            </div>
            <div class="form-group">
                <label for="givenName">Vorname</label>
                <input type="text" class="form-control" id="givenName" required="required" 
                    oninvalid="this.setCustomValidity('Gib bitte den Vornamen des Teilnehmers an.')" oninput="setCustomValidity('')">
            </div>
            <div class="form-group">
                <label for="familyName">Nachname</label>
                <input type="text" class="form-control" id="familyName" required="required" 
                    oninvalid="this.setCustomValidity('Gib bitte den Nachnamen des Teilnehmers an.')" oninput="setCustomValidity('')">
            </div>
            <div class="form-group">
                <label for="gender">Mädchen / Junge</label>
                <select id="gender" class="form-control" required="required"
                    oninvalid="this.setCustomValidity('Gib bitte an, ob der Teilnehmer ein Mädchen oder ein Junge ist.')" oninput="setCustomValidity('')">
                    <option value="" disabled selected></option>
                    <option value="f">Mädchen</option>
                    <option value="m">Junge</option>
                </select>
            </div>
            <div class="form-group">
                <label for="yearOfBirth">Geburtsjahr</label>
                <select id="yearOfBirth" class="form-control" required="required"
                    oninvalid="this.setCustomValidity('Gib bitte das Geburtsjahr des Teilnehmers an.')" oninput="setCustomValidity('')">
                    <option value="" disabled selected></option>
                </select>
            </div>
            <div class="form-group">
                <label for="rentalNotebook">Ich brauche ein Leih-Notebook</label>
                <select id="rentalNotebook" class="form-control" required="required"
                    oninvalid="this.setCustomValidity('Gib bitte an, ober der Teilnehmer ein Leih-Notebook braucht.')" oninput="setCustomValidity('')">
                    <option value=""></option>
                    <option value="no">Nein</option>
                    <option value="yes">Ja</option>
                </select>
            </div>
            <div class="form-group">
                <label for="email">Email Adresse</label>
                <input type="email" class="form-control" id="email" required="required"
                    oninvalid="this.setCustomValidity('Gib uns bitte eine Email-Adresse, unter dir wir dich bei Fragen oder Termin-Änderungen erreichen können.')" oninput="setCustomValidity('')">
            </div>
            <div class="pull-right">
                <button type="submit" class="btn btn-material-light-blue-700">Anmelden</button>
            </div>
        </form>
    </div>
  </div>
</div>


## <a name="Uni" />Ort

TODO

