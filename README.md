# ca
Contracts Advance Appcues
<script>
  (function(a, ns, cb, l) {
    document.getElementsByTagName('head')[0].appendChild(l);
    window[ns] = function(callback) {
      (window[ns].q = window[ns].q || []).push(callback);
      if (window[a] != null) {
        while (window[ns].q.length) {
          cb = window[ns].q.shift();
          if (typeof cb === 'function') cb();
        }
      }
    };
  })('Appcues', 'AppcuesReady');
</script>

<script>
  // You could then use Appcues immediately by calling AppcuesReady() with a callback:
  AppcuesReady(function() {
    Appcues.identify('userId', {email: 'owen@contractsadvance.co.uk'});
  });
</script>

  // Load the script at any time later:
  
<script src="//fast.appcues.com/23.js" async defer onload="AppcuesReady()"></script>

  // idea for property names to be included at this point - this will need to be recoded for application - currently in .js
  
created_at: "<%= current_user.created_at %>"
email: "<%= current_user.email %>"
username: "<%= current_user.username %>"
password: "<%= current_user.password %>"
permission_level: "<%= current_user.permission %>"
account_id: "<%= current_user.accountid %>"
plan_type: "<%= current_user.plan %>"
isInstalled: "<%= current_user.installedstatus %>"


currentDayOfWeek: currentTimeString.getDay(),  // 0=Sunday, 6=Saturday  	
currentDayOfMonth: currentTimeString.getDate(),  // 1-31 	
currentHour: currentTimeString.getHours(),   // 0-23 	
currentMonth: currentTimeString.getMonth()   // 0=January, 11=December <br>
