# Wireless-Mana-Automation-System
System Overview This setup consists of:  Head Controller (Master Computer) → Displays mana levels, alerts, and logs data.  Slave Units (Individual Mana Pools) → Each slave unit controls one mana pool.  Wireless Modems → Connect all computers wirelessly.  Advanced Monitor → Displays mana levels and automation status.


How To:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
1.Set Up the Slave Units
Each slave unit manages its own mana pool and sends updates to the head controller.

Installation Steps for Slave Units:
Place a ComputerCraft Computer near each mana pool.

Attach a Wireless Modem to the computer.

Connect a Redstone Comparator to the mana pool.

Ensure comparators face outward to read mana levels.

Run the slave program on each computer.



2.Set Up the Head Controller
The Head Controller (Master Computer) displays mana levels, sends alerts, and stores trend data.

Installation Steps for Head Controller:
Place an Advanced Computer near your main setup.

Attach a Wireless Modem to communicate with slave units.

Connect an Advanced Monitor for graphical display.

Run the head controller program.



3.Final Steps
Run the Slave Program on each pool's computer.

Run the Head Controller Program on the master computer.

Watch mana levels update wirelessly in real-time.

Review logs via mana_log.txt for historical trends.
