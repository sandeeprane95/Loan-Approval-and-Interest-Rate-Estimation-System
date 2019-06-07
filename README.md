## Loan Approval and Interest Rate Estimation System  

The Loan Approval and Interest Rate Estimation System is an application developed in Netica using a combination of Bayesian networks and influence diagram technology. The system is designed to help its users determine if their current financial background, credit score and residential status are strong enough to help them get their loan request approved. The system performs a brief analysis of the current situation of the user by allowing the users to update the root nodes (nodes without parents) of the Bayesian network, recalculates the probabilities of all nodes from the root to the leaf in order to determine whether he/she is a good candidate for a loan application. In addition, it uses the decision net to estimate if the interest rate applied on his/her loan should be low or high. Such an application is not only beneficial for a bank in determining whether or not to approve a loan request, but also a handy application for the person seeking loan.  

### How to run the code -  

1. Download the ‘LoanApprovalSystem.neta’ file and open it in Netica.  
2. Click ‘Compile Net’ in the menu bar.  
3. Click on any input nodes to toggle between its values.  
4. This would update the probabilities at all the dependent nodes and hence the final output node would also be updated.  
5. The probability of the output node indicates the chances of each possible outcome.  
6. Depending on all these probability values, the utility node which itself depends on other nodes guides the decision of the decision node.  