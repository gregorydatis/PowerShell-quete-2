# PowerShell-quete-2

  Id CommandLine                                                                                             
  -- -----------                                                                                             
   1 New-Item -ItemType Directory -Path C:\ -Name EvenFolder...                                              
   2 New-Item -ItemType File -Path C:\ -Name File1                                                           
   3 New-Item -ItemType File -Path C:\ -Name File2                                                           
   4 New-Item -ItemType File -Path C:\ -Name File3                                                           
   5 New-Item -ItemType File -Path C:\ -Name File4                                                           
   6 New-Item -ItemType File -Path C:\ -Name File5                                                           
   7 New-Item -ItemType File -Path C:\ -Name File6                                                           
   8 New-Item -ItemType File -Path C:\ -Name File7                                                           
   9 New-Item -ItemType File -Path C:\ -Name File8                                                           
  10 New-Item -ItemType File -Path C:\ -Name File9                                                           
  11 New-Item -ItemType File -Path C:\ -Name File10                                                          
  12 Get-ChildItem                                                                                           
  13 clear                                                                                                   
  14 Set-Location                                                                                            
  15 Get-ChildItem -Path C:\EvenForlder                                                                      
  16 Move-Item -Path C:\FolderTest1\File2 -Destination C:\EvenFolder...                                      
  17 Get-ChildItem -Path C:\FolderTest1...                                                                   
  18 ...                                                                                                     
  19 Move-Item -Path C:\FolderTest1\File2 -Destination C:\EvenFolder...                                      
  20 Get-ChildItem -Path C:\FolderTest1                                                                      
  21 Move-Item -Path C:\FolderTest1\File2.txt -Destination C:\EvenFolder                                     
  22 Get-ChildItem -Path C:\                                                                                 
  23 Get-ChildItem -Path C:\FolderTest1                                                                      
  24 ...                                                                                                     
  25 Remove-Item -Path C:\EvenForlder                                                                        
  26 Remove-Item -Path C:\OddForlder                                                                         
  27 Remove-Item -Path C:\FolderTest1                                                                        
  28 Remove-Item -Path C:\FolderTest2                                                                        
  29 New-Item -ItemType File -Path C:\FolderTest1 -Name File1...                                             
  30 New-Item -ItemType File -Path C:\FolderTest1 -Name File1                                                
  31 New-Item -ItemType Directory -Path C:\ -Name FolderTest1                                                
  32 New-Item -ItemType Directory -Path C:\ -Name FolderTest2                                                
  33 Get-ChildItem -Path C:\                                                                                 
  34 New-Item -ItemType File -Path C:\FolderTest1 -Name File1...                                             
  35 Get-ChildItem -Path C:\FolderTest1                                                                      
  36 Get-ChildItem -Path C:\FolderTest2                                                                      
  37 Move-Item -Path C:\FolderTest1\File2 -Destination C:\EvenFolder...                                      
  38 Move-Item -Path C:\FolderTest1\File1 -Destination C:\OddFolder...                                       
  39 Get-ChildItem -Path C:\EvenFolder                                                                       
  40 Get-ChildItem -Path C:\OddFolder                                                                        

 Répertoire : C:\EvenFolder


Mode                 LastWriteTime         Length Name                                                       
----                 -------------         ------ ----                                                       
-a----        16/03/2026     11:13              0 File10                                                     
-a----        16/03/2026     11:13              0 File2                                                      
-a----        16/03/2026     11:13              0 File4                                                      
-a----        16/03/2026     11:13              0 File6                                                      
-a----        16/03/2026     11:13              0 File8                                                      


    Répertoire : C:\OddFolder


Mode                 LastWriteTime         Length Name                                                       
----                 -------------         ------ ----                                                       
-a----        16/03/2026     11:13              0 File1                                                      
-a----        16/03/2026     11:13              0 File3                                                      
-a----        16/03/2026     11:13              0 File5                                                      
-a----        16/03/2026     11:13              0 File7                                                      
-a----        16/03/2026     11:13              0 File9                                                      




