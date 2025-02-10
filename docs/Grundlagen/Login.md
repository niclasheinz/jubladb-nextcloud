# Login

Für den ersten Login benötigst du das Administratoren-Login. Mit diesem kannst du wie im Kapitel 2 beschrieben, die Nextcloud für deine Schar konfigurieren. Es ist empfehlenswert, dass du zuerst das Design anpasst (siehe Kapitel 2.1) und dann die Authentifizierung mittels der Jubla.db aktivierst (siehe Kapitel 2.4).

## Adminbenutzer absichern mittels 2-Faktor-Authentifizierung (2FA)

Damit deine Nextcloud-Instanz sicher ist, muss der Adminbenutzer auch abgesichert sein. Als erstes, generiere Backupcodes. Diese kannst du verwenden, wenn du wegen dem Password oder der 2FA dich nicht mehr einloggen kannst. Speichere diese an einem sicheren Ort ab. Danach aktiviere wie in Bild 4 und 5 beschrieben die 2FA

<style>
.step-table {
    border-collapse: separate;
    border-spacing: 10px;
    width: 100%;
}
.step-table td {
    border: none;
    padding: 0;
    position: relative;
}
.step-number {
    position: absolute;
    bottom: 10px;
    left: 10px;
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background-color: #007bff;
    color: white;
    text-align: center;
    line-height: 30px;
    font-weight: bold;
    z-index: 1;
}
.step-table img {
    display: block;
    width: 100%;
    height: auto;
}
</style>

<table class="step-table">
    <tr>
        <td>
            <span class="step-number">1</span>
            <img src="../../assets/Admin/Sicherheitseinstellungen/Sicherheitseinstellungen_2FA-1.jpg" alt="2FA-1">
        </td>
        <td>
            <span class="step-number">2</span>
            <img src="../../assets/Admin/Sicherheitseinstellungen/Sicherheitseinstellungen_2FA-2.jpg" alt="2FA-2">
        </td>
    </tr>
    <tr>
        <td>
            <span class="step-number">3</span>
            <img src="../../assets/Admin/Sicherheitseinstellungen/Sicherheitseinstellungen_2FA-3.jpg" alt="2FA-3">
        </td>
        <td>
            <span class="step-number">4</span>
            <img src="../../assets/Admin/Sicherheitseinstellungen/Sicherheitseinstellungen_Backupcodes_1.jpg" alt="Backupcodes_1">
        </td>
    </tr>
    <tr>
        <td>
            <span class="step-number">5</span>
            <img src="../../assets/Admin/Sicherheitseinstellungen/Sicherheitseinstellungen_Backupcodes_2.jpg" alt="Backupcodes_2">
        </td>
        <td>Damit du allen Benutzern in der Gruppe „admin“ die 2FA erzwingen möchtest, gehe wie bei Kapitel 2.2.1 vor.</td>
    </tr>
</table>



