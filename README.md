# mems_beadando
Eredeti projektmunkánk egy gyroszkóppal és egy gps-szel elátott Raspberry pi 3b+ on futó motor riasztó lett volna. Ha a rendszer élesítése után döntik meg a motorbiciklit, a gps bekapcsol és bizonyos időközönként koordinátákat küld ki Twitterre.
A választott projektmunkánkat azonban előre nem látott teknikai okokból nem tudtuk megvalósítani, ezért apró változtatásra szántuk el magunkat. 

Jelen helyzetben a Raspberry egy SenseHat-tel üzemel. Feladata, egy nyomvonalon haladó jármű aktuális helyzetének érzékelése.
Ha a jármű kritikus helyzetbe kerül (felborul), a program Twitter üzenetet oszt meg. 
