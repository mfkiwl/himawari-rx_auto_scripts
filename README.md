# himawari-rx_auto_scripts
Auto scripts for [**sam210723/himawari-rx**](https://github.com/sam210723/himawari-rx).

**himawari-rx__auto.bat** is the main script for start TSDuck, and start **himawari-rx__decode.bat** automatic when TSDuck is terminated.

**himawari-rx__decode.bat** is the script for start himawari-rx to receive files, and make pictures automatic. It will start automatic by the **himawari-rx__auto.bat** script.

**time_monitor_to_terminate_TSDuck.bat** is the script to terminate **all TSDuck processes (tsp.exe)** automatic every 10 minutes (when **the last digit** of **minute** is **5**), then will make **himawari-rx__decode.bat** started automatic by **himawari-rx__auto.bat**. <br>
**Notice:** **all TSDuck processes (tsp.exe)** will be **terminated** when it's time to **terminate** **tsp.exe** by this script!


