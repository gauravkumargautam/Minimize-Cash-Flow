# Minimize-Cash-Flow
Developed and implemented utilizing HTML, CSS, and JavaScript to ease several transactions into minimal transactions to make transactions more accessible and efficient. The underlying data structure used for the implementation of the project is heaps that can be visualized through a directed graph.

![project_image](https://github.com/gauravkumargautam/Minimize-Cash-Flow/assets/144528033/3e0ffffc-b807-40b7-8fac-19ae772c5f02)
**Minimize Cash Flow Algorithm:**

Do following for every person Pi where i is from 0 to n-1 :
1. Compute the net amount for every person. The net amount for person ‘i’ can be computed be subtracting sum of all debts from sum of all credits.
2. Find the two persons that are maximum creditor and maximum debtor. Let the maximum amount to be credited maximum creditor be maxCredit and maximum amount to be debited from maximum debtor be maxDebit. Let the maximum debtor be Pd and maximum creditor be Pc.
3. Find the minimum of maxDebit and maxCredit. Let minimum of two be x. Debit ‘x’ from Pd and credit this amount to Pc
4. If x is equal to maxCredit, then remove Pc from set of persons and recur for remaining (n-1) persons.
5. If x is equal to maxDebit, then remove Pd from set of persons and recur for remaining (n-1) persons.

**How to use :**
* Click here : https://minimize-cashflow-website.netlify.app/
* Click on the get new problem icon at the bottom
* Finally click the solve button to get the solution 
