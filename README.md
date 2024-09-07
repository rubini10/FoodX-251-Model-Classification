Nada Mohamed 857606
Alessia Rubini 851890


Visual Information Processing and Management
-Tutti i notebook sono già stati precedentemente eseguiti-


Elaborazione dei dati (svolta in matlab)
All’interno di questa ci sono i seguenti file:
-	estrazione_outliers_ResNet50: usato per identificare gli outliers all’interno del train set
●	output → outliers identificati nel train
-	after_outlier_identification: una volta identificati gli outliers, questo viene utilizzato per estrarli dal train originale in modo da ottenere il train pulito
●	output → train pulito senza le immagini fuori contesto identificate
-	sampling: successivamente è stato utilizzato questo per bilanciare (mediante undersampling e oversampling) il train pulito ottenuto al punto precedente
●	output → train bilanciato
-	brisque: usato per analizzare il test set degradato e non, per poi identificare la quantità -circa- di elementi degradati nel primo
-	data_augmentation_degradated: una volta determinata la quantità di dati da degradare nel train set, questo viene utilizzato per svolgere tale compito. 
●	output → test degradato

Modelli di classificazione (svolta in python)
All’interno di questa ci sono tre cartelle:
-	resnet101
-	resnet50
-	efficientnet -modello selezionato-

All’interno di ognuna di queste cartelle ci sono due notebook, uno con il modello allenato sul train degradato e l’altro sul train originale.
Con ogni notebook è stato caricato il modello addestrato corrispondente.

Inoltre all’interno di questa cartella ci sono due notebook corrispondenti all’analisi visiva riportata nel ppt; una eseguita sul test degradato e l’altra sul test non degradato.

Facoltativi
Qui vengono riportati notebook relativi ai task facoltativi svolti ovvero:
-	similarity (svolta in python)
-	image-detection (svolta in matlab) + 
food recognition (svolto in python)
