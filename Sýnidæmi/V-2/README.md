# Tafla &lt;table>

Tabular Data <td> er eina tagið sem er hannað til að sækja gögn af miðlara í hvert sinn sem vefsíða er opnuð, jafnvel þegar flett er á milli síðna. Það er mjög gagnlegt þegar um er að ræða upplýsingar sem uppfærast daglega eða oftar.

Töflur henta ekki í skipulagshönnun vefsíðu. Önnur tög henta betur fyrir texta og myndir. 
"Table" tagið er erfitt að eiga við þegar kemur að sveigjanleika vefsíðu og best að nota það ekki nema þegar um gagnvirkar færslur er að ræða.  En ef um tiltötlulega fáa dálka er að ræða er hægt að nota aðferð sem er [útskrýrð nánar hér](https://allthingssmitty.com/2016/10/03/responsive-table-layout/)

```HTML
<table>
    <caption>Titill töflu</caption>
    <thead>
        <tr>
            <th scope="col"> </th>
            <th scope="col">A</th>
            <th scope="col">B</th>
            <th scope="col">C</th>
            <th scope="col">D</th>
        </tr>
        <!-- The scope attribute specifies whether a header cell is a header for a column, row, or group of columns or rows.
        Note: The scope attribute has no visual effect in ordinary web browsers, but can be used by screen readers. -->
    </thead>
    <tbody>
        <tr>
            <td scope="row" data-label="AÖ">E</td>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
        </tr>
        <tr>
            <td scope="row" data-label="AÖ">F</td>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
        </tr>
        <tr>
            <td scope="row" data-label="AÖ">G</td>
            <td data-label="A">Atli</td>
            <td data-label="B">Bára</td>
            <td data-label="C">Cesar</td>
            <td data-label="D">Dóra</td>
        </tr>
    </tbody>
</table>	

```

# Form &lt;form>

```HTML

    <form action="https://www.w3schools.com/html/html_forms.asp" method="GET">
        <input type="submit" value= "Ná í upplýsingar um form tagið">
      </form>


```
