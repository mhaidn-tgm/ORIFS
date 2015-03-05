# ORIFS
Documented installation of ORIFS and a comparison to other distributed file systems

# Taskdefinition


Installation und Implementierung
--------------------------------

"Ori is a distributed file system built for offline operation and empowers the user with control over synchronization operations and conflict resolution. We provide history through light weight snapshots and allow users to verify the history has not been tampered with. Through the use of replication instances can be resilient and recover damaged data from other nodes." [1]

Installieren Sie Ori und testen Sie die oben beschriebenen Eckpunkte dieses verteilten Dateisystems (DFS). Verwenden Sie dabei auf jeden Fall alle Funktionalitäten der API von Ori um die Einsatzmöglichkeiten auszuschöpfen. Halten Sie sich dabei zuallererst an die Beispiele aus dem Paper im Kapitel 2 [3].  Zeigen Sie mögliche Einsatzgebiete für Backups und Roadwarriors (z.B. Laptopbenutzer möchte Daten mit zwei oder mehreren Servern synchronisieren). Führen Sie auch die mitgelieferten Tests aus und kontrollieren Sie deren Ausgaben (Hilfestellung durch Wiki [2]).
Gegenüberstellung

Wo gibt es Überschneidungen zu anderen Implementierungen von DFS? Listen Sie diese auf und dokumentieren Sie mögliche Entscheidungsgrundlagen für mindestens zwei unterschiedliche Einsatzgebiete. Verwenden Sie dabei zumindest HDFS [4] und GlusterFS [5] als Gegenspieler zu Ori. Weitere Implementierungen sind möglich aber nicht verpflichtend. Um aussagekräftige Vergleiche anstellen zu können, wäre es von Vorteil die anderen Systeme ebenfalls - zumindest oberflächlich - zu testen.
Info

Gruppengröße: 2 Mitglieder
Gesamtpunkte: 16

  Installation und Testdurchlauf von Ori: 2 Punkte
  Einsatz/Dokumentation der Ori API (replicate, snapshot, checkout, graft, filelog, list, log, merge, newfs, pull, remote, removefs, show, status, tip, varlink): 8 Punkte
  Gegenüberstellungstabelle: 4 Punkte
  Einsatz der Gegenspieler: 2 Punkte

Quellen
-------

[1] Ori File System, Stanford Website, online: http://ori.scs.stanford.edu/, visited: 2015-03-02
[2] Ori File System, Bitbucket Wiki, online: https://bitbucket.org/orifs/ori/wiki/Home, visited: 2015-03-02
[3] Ali José Mashtizadeh, Andrea Bittau, Yifeng Frang Huang, David Mazières. Replication, History, and Grafting in the Ori File System. In Proceedings of the 24th Symposium on Operating Systems Principles, November 2013. Paper.
[4] Apache Hadoop FileSystem, http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html, visited: 2015-03-02
[5] GlusterFS, http://www.gluster.org/documentation/howto/HowTo/, visited: 2015-03-02
