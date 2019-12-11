# FintechSocDapp
<h4>To run the application</h4>
<ol>
<li>npm install lite-server --save-dev</li>
<li>truffle compile</li>
<li>truffle migrate --reset</li>
<li>truffle test</li>
<li>npm run dev</li>
</ol>
<h4>Notes</h4>
<ul>
<li>Step 4 should have 5 passing and 1 failing</li>
<li>If when you try the functionalities and there is an rpc error, try resetting your metamask account</li>
</ul>

<br>
<br>
<br>

| Features                                         | Clean up                                                  |
|--------------------------------------------------|-----------------------------------------------------------|
| Exchange (2nd hand market)                       | ~~Validation: Date of event-> check if date is in the past~~  |
| Bidding - VIP seats                              | Removal of event on passing the date                      |
| Subscription Service (membership for discounts?) | Validation: Check duplicate of event names                |
| ~~Create Event, Buy Event, Read Event~~          | Store price, date and location on the chain               |
|                                                  | ~~Validation: name doesnt exceed 32 char and is only ascii chars~~ |

<br>
<br>
<br>
<br>

Based off: https://www.trufflesuite.com/tutorials/pet-shop
