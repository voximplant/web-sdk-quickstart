<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Quickstart demo</title>
  <script src="//cdn.voximplant.com/edge/voximplant.min.js"></script>
</head>
<body>
  <button id="jsMakeCall">Make call</button>
<script>
  const sdk = VoxImplant.getInstance();
  sdk.init()
    .then(()=>{
      console.log('This code is executed after SDK successfully initializes');
      sdk.connect()
    })
    .then(()=>{
      console.log('This code is executed after SDK is successfully connected to Voximplant');
      sdk.login('username@appname.accname.voximplant.com','pass')
    })
    .then(()=>{
      console.log('This code is executed on successfull login');
      document.getElementById('jsMakeCall').addEventListener('click',()=>{
        const call = sdk.call('*');
        call.on(VoxImplant.CallEvents.Connected, () => console.log('You can hear audio from the cloud'));
        call.on(VoxImplant.CallEvents.Failed, (e) => console.log(`Call failed with the ${e.code} error`));
        call.on(VoxImplant.CallEvents.Disconnected, () => console.log('The call has ended'));
      },false);
      sdk.on(VoxImplant.Events.IncomingCall, (e) => {
        e.call.answer();
        console.log('You can hear audio from the cloud');
        e.call.on(VoxImplant.CallEvents.Disconnected, () => console.log('The call has ended'));
        e.call.on(VoxImplant.CallEvents.Failed, (e) => console.log(`Call failed with the ${e.code} error`));
      });
    })
    .catch((e)=>{
      console.log(e);
    });
</script>
</body>
</html>
