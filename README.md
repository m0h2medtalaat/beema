# Beema
Beema iOS mobile Application
<a href="https://media.giphy.com/media/LRUbDt1zE3myvSsJZT/source.gif"><img src="https://media.giphy.com/media/LRUbDt1zE3myvSsJZT/source.gif" title= "BloodBankApp"></a>
<iframe src="https://player.vimeo.com/video/450791898" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
<script>
    require(['https://player.vimeo.com/api/player.js'], function (Player) {
        var iframe = document.querySelector('iframe');
        var player = new Player(iframe);

        player.on('play', function() {
            console.log('played the video!');
        });
    });
</script>
