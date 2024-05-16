^.+?((?:\d+\.){3}\d+).+$ et remplacer par $1 --> extraire les ip

^(.*?)$\s+?^(?=.*^\1$) --> supprimer les lignes en doublon dans le fichier (regex + .Matches newline)
