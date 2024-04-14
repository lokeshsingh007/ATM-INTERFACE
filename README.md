# ATM-INTERFACE
print("WELCOME IN HDFC BANK ATM")

print(" 1->transection history")
print(" 2->withdraw")
print(" 3->deposit")
print(" 4->transfer")
print(" 5->quit" )

option=int(input(" choose an option :"))

if option==1:
    print('''transection history:last payment :23000.cr rs last payment :23000.cr rs 
          last payment :23000.cr rs last payment :23000.cr rs''')

elif option==2:
    print("withdraw")
    
    withdraw=int(input(" enter the amount: "))

    
    pin=int(input("enter the your four digit Atm pin"))
    if pin==1234:
        print(" right pin number\n ")
      
        print("collect your cash......")

 
    else:
        print("invalid  pin")
if option==3:
    print("deposit section:")
    deposit=int(input("enter the amount you want to depose"))
    print("successfully deposit")
if option==4:
        print("transfer section:")
        acount=int(input(" enter the acount number: "))
        amount=int(input(" enter the amount: "))
        pin=int(input("  enter the your four digit Atm pin:  "))
        pin=1234
        if pin==1234:
             print("valid pin")
             
        else:
             print("wrong pin")
   
        print("transfer successfully")

    
