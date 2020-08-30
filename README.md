pragma solidity 0.4.12 <= 0.6.12;

contract MedicalData

 { 
             string MedicalName;
             string addss;
             string MedicalPhoneNumber;
             string MedicineName;
             int MedicinePrice ;
             string MedicineExpireyDate;
             string MedicalOwnerName;
             int NumberOfMedicineSale;
 
 function MedicalData(string newMedicalName, string newAddrs, string newMedicalPhoneNumber, string newMedicineName,
 int newMedicinePrice, string newMedicineExpiryDate, string newMedicalOwnerName, int newNumberOfMedicineSale)
 
 public
           {
                 MedicalName= newMedicalName;
                 addss = newAddrs;
                 MedicalPhoneNumber = newMedicalPhoneNumber;
                 MedicineName = newMedicineName;
                 MedicinePrice = newMedicinePrice;
                 MedicineExpireyDate = newMedicineExpiryDate;
                 MedicalOwnerName = newMedicalOwnerName;
                 NumberOfMedicineSale = newNumberOfMedicineSale;
              
            }
         
 
 function getMedicalData() public returns(string, string,string,string,int,string,string,int)
 
            { 
                return(MedicalName, addss,MedicalPhoneNumber, MedicineName, MedicinePrice, MedicineExpireyDate, MedicalOwnerName, NumberOfMedicineSale);
            }   
 
 
  }
