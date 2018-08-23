# diestelkind_datenbank

Diestelkind .. war mal ein Projekt von mir. 
Ich habe alle Videos des ersten Jahres der Mahnwachen gesammelt .. 
Nach Ort und Datum sortiert .. 

# über 4500 Videolinks  / etwas über 1 Jahr von der ersten Mahnwache an. 

## Video Archiv der Mahnwachen in Deutschland, Österreich und Schweiz nach Datum und Ort sortiert. 

 

      
      CREATE TABLE IF NOT EXISTS `group` (
        `id` int(10) NOT NULL AUTO_INCREMENT,
        `title` varchar(250) NOT NULL,
        `desc` text NOT NULL,
        `cat` varchar(100) NOT NULL,
        `date` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
        `ort` varchar(100) NOT NULL,
        `land` varchar(50) NOT NULL,
        `erstellt` timestamp NOT NULL DEFAULT '0000-00-00 00:00:00',
        `edit` timestamp NOT NULL DEFAULT '0000-00-00 00:00:00',
        `autorid` int(5) NOT NULL,
        `open` int(1) NOT NULL COMMENT '0 = nein; 1 = ja',
        `location` varchar(250) NOT NULL,
        `plz` varchar(8) NOT NULL,
        `language` varchar(80) NOT NULL,
        `lizenz` varchar(120) NOT NULL,
        `authorname` varchar(100) NOT NULL,
        PRIMARY KEY (`id`)
      ) ENGINE=InnoDB  
      --DEFAULT CHARSET=utf8 AUTO_INCREMENT=8 ;

 
## Das war mal das Projekt

[Zum Video](https://youtu.be/PlcGsR37mgM)
[![IMAGE ALT TEXT](http://img.youtube.com/vi/PlcGsR37mgM/0.jpg)](http://www.youtube.com/watch?v=PlcGsR37mgM "Video Title")
