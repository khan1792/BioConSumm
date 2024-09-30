# BioConSumm
This is the repo for BioConSumm project. 
list_of_paper_titles.csv is a list of titles of the papers we used for text summarization model training.

## Instruction for data collection (full papers) from the Web of Science
1. Visit https://www.webofscience.com/wos/woscc/basic-search. If you are affiliated with an institution that subscribes to Web of Science, you can access the webpage through your institution's network or VPN. If you are a personal subscriber, you will be prompted to log in.
2. In the left box, select 'Web of Science Categories.'
![image](https://github.com/user-attachments/assets/617b0207-6244-45ca-9f5c-701bd5385ac6)
3. Type 'biodiversity' in the right box, then select 'Biodiversity Conservation,' and click the purple 'Search' button. 
![image](https://github.com/user-attachments/assets/384ff1d1-1c7e-43a4-a2b9-e003a0b098da)
4. You can filter publications based on year, document type, or other WoS filters. For example:
![image](https://github.com/user-attachments/assets/96625a04-e737-4295-b255-61628c4686c4)
5. Click Export and select EndNote Desktop
![image](https://github.com/user-attachments/assets/2c21016a-ef91-49c2-9c24-761e28f38e7a)
6. Since the maximum number of records per query is 500 or 1,000, you may need to export all records through multiple queries. Choose the second option (Records from ... to ...) and enter the record range (e.g., 1 to 500) → select 'Full Record' → click 'Export'.
![image](https://github.com/user-attachments/assets/844d4a7b-20e7-44ef-9ef1-1a6f4cb28120)
7. Open EndNote X9, click File -> New to create a new library (.enl file)
![image](https://github.com/user-attachments/assets/581a130f-8e61-4edb-ab71-165e834ec88b)
8. Click Import, and choose a file you downloaded from WoS (you can only import one file per time), and have the following settings:
   Import Option: ISI-CE
   Duplicates: Discard Duplicates
   Text translation: No translation
![image](https://github.com/user-attachments/assets/e7021e89-d0e3-4cad-b6e5-9556e26a07a4)
9. Select multiple records, right-click, and choose 'Find Full Text' → 'Find Full Text.' EndNote will automatically download the PDF files. The maximum number of papers you can download per query through EndNote is 100 or 200. Please repeat this step if not all papers have been queried.
![image](https://github.com/user-attachments/assets/10226b1b-fe04-4886-bd53-f51fe48a0e43)

 
      
