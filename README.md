# pseudo-code

Définir une fonction NombreMaximumDeBonbons(argent, prix):                            
    Si argent <= 0 ou prix <= 0:                                     
        Retourner 0  # Vérifier que l'argent et le prix sont strictement positifs                                    
    
    bonbonsAchetés = 0  # Initialisation du compteur de bonbons                       
    
    Tant que argent >= prix:                                                   
        argent -= prix  # Soustraire le prix d'un bonbon à l'argent disponible                           
        bonbonsAchetés += 1  # Augmenter le compteur de bonbons                                       
    
    Retourner bonbonsAchetés  # Retourner le nombre maximum de bonbons achetés                                  
Fin de la fonction
