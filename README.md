# YouTube-JS-Video-Action-Variables

function() {
  var status = {{Video Status}};
  switch (status) {
    case 'start':
      return 'Start playing';
    case 'pause':
      return 'Pause';
    case 'buffering':
      return 'Buffering';
    case 'progress':
      return 'Reached ' + {{Video Percent}} + '%';
    case 'complete':
      return 'Reached the end';
  }
 
}
