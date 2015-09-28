# FireBackupMaps
Fire Backup Maps

function initMap() {
  // Create a map object and specify the DOM element for display.
  var map = new google.maps.Map(document.getElementById('map'), {
    center: {lat: -43.5534390157778, lng: -96.7311049115714},
    scrollwheel: false,
    zoom: 8
  });
}
