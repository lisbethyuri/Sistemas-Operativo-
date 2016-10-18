#!/bin/bash
Cd directorio donde clonaste tu repositorio del git
git add .
Git commit -a -m "segundo"
Gut push origin master
DIA=`date +"%d/%m/%Y"`
HORA=`date +"%H:%M"`

echo "Hoy es el $DIA y la hora actual es $HORA!"
