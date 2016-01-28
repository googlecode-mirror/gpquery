**GPQuery** is a web interface that allows users to retrieve and compare various Grand Prix Racing statistics dating back to the start of the World Championship in 1950.

The front-end interface predominately utilises jQuery and AJAX.  The back-end is comprised of PHP and MySQL, the latter being provided by a database image available from the [Ergast Developer API](http://ergast.com/mrd).

Emphasis is placed on:
  * A clean, simple-to-use, and streamlined interface requiring minimal input from the user
  * An interactive results display that allows users to manipulate and compare data
  * Efficiency with regards to hardware and network resources


---


### Features ###

The following options are available for all historical data from 1950 and onwards and will be implemented in the prototype:
  * **Drivers** - Driver information, career records, and various statistics.
  * **Seasons** - Grands Prix, driver standings, constructor standings, and various statistics.
  * **Races** - Race results, driver standings, constructor standings, and various statistics.

Subsequent versions after the prototype will also include:
  * **Constructors** - Constructor information, records, and various statistics.
  * **Circuits** - Circuit information, Grands Prix, and various statistics.

Due to limited availability of data, the following options are available only for recent seasons and will likely be implemented in subsequent versions after the prototype:
  * **Qualifying**
  * **Lap Times**
  * **Pit Stops**


---


### Technologies ###

  * [Twitter Bootstrap](http://getbootstrap.com/)
  * [jQuery](http://jquery.com/)
  * [DataTables for jQuery](http://datatables.net/)
  * [PHP Data Objects (PDO)](http://www.php.net/manual/en/book.pdo.php)