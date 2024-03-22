# Sentinel

First, deploy a watchlist, in this case for newly added users or deleted users. Other examples of watchlists could be for importing a list of users with Privileged access who could then be put on an allowlist to avoid alerts being created by them. Or, a watchlist for former employees could be created and then a blocklist used to prevent them from logging on to the network.

<br/>
<img src="https://github.com/mdnorris1/SentinelLab/blob/main/watchlist.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Next, create hunt queries for any New Users in Entra and deleted Users also.


<br/>
<img src="[assets/stats .png](https://github.com/mdnorris1/SentinelLab/blob/main/hunt1.png)" height="80%" width="80%" alt="ifconfig command"/>
<br />

An existing UEBA rule can be customised for your context.

<br/> 
<img src="assets/src ip.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Then a new query can be edited and then click run to execute it.

<br/> 
<img src="assets/dest ip.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Finally, logs can be analysed.

<br/>
<img src="assets/visualisation.png" height="80%" width="80%" alt="ifconfig command"/>
<br />


