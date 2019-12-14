# Gem5-ex3 - McPAT

## Βήματα της εργασίας
### 1ο Βήμα - Εξοικείωση με τον εξιμοιωτή McPAT

Clone github McPat

``` git clone https://github.com/kingmouf/cmcpat.git my_mcpat ```

*Πιθανόν χρειάζονται τα παρακάτω πακέτα*
- ```sudo apt install libc6-dev-i386``` για 32bit  ή ```sudo apt-get install g++-multilib``` για 64bit
- ```sudo apt install gcc-7-multilib g++-7-multilib```

Compile with make

- ```cd my_mcpat/mcpat```
- ```make```

Εκτέλεση του McPAT για τον επεξεργαστή *Xeon* από το φάκελο ProcessorDescriptionFiles
- ```./mcpat -infile ProcessorDescriptionFiles/Xeon.xml -print_level 1```
*-print_level 1,2,3,4,5*

#### Ερωτήματα

