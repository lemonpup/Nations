Dictatorship Sudocode
=====================

public class dictatorship implements Government {

string name;

boolean isAllowed() {
check config if the gov type is allowed
}

string getName() {
return this.name;
}

boolean hasFunds(Player sender) {
if core.getPlayer(sender).getBalance() = core.getDictatorshipCost() //core checks config for dictatorship cost
   return true
else return false
}

boolean typeAllowsStaffVoting() {
return false
}

boolean typeAllowsResidentVoting() {
return false
}
