<!DOCTYPE html>
<html>
    <title>WELCOME</title>
    <script src="script.js"></script>
    <body style="background: rgb(0, 0, 0);" text="white">
    <center><H1>WELCOME</H1>
    <p>NAME</p>
    <input type="text" name="user"/><br><br>
    <input type="submit" required/>
    <p>WHICH GAME ARE YOU DOWNLOADING</p>
    <select id="ddselect">
        <option>GTA 5</option>
        <option>RDR2</option>
        <option>RESIDENT EVIL 4</option>
        <option>SEA OF THIEVES</option>
        <option>VALORANT</option>
    </select><br><br>
    <p>ARE YOU A YOUTUBER</p>
    <form>
    <input type="radio" name="container" value="YES">YES</input><br>
    <input type="radio" name="container" value="No">NO</input><br><br>
    </form>
    <p>WHICH GAME DO YOU WANT TO DOWNLOAD</p><br>
    <button id="REDIRECT">GTA 5</button>
    <script>
        document.querySelector('#REDIRECT')
        .addEventListener('click' , () => {
            window.location.href = 'https://steamunlocked.net/grand-theft-auto-v-free-v4-download/' ;
        });
    </script><br><br>

    <button id="REDIRECTORY">RDR2</button>
    <script>
    document.querySelector('#REDIRECTORY')
    .addEventListener('click' , () => {
        window.location.href = 'https://steamunlocked.net/30-red-dead-redemption-2-free-v14-download/' ;
    });
</script><br><br>

<button id="REDIRECTING">RESIDENT EVIL 4</button>
<script>
    document.querySelector('#REDIRECTING')
    .addEventListener('click' , () => {
        window.location.href = 'https://steamunlocked.net/resident-evil-4-free-download/' ;
    })
</script><br><br>

<button id="REDIRECTINGS">SEA OF THIEVES</button>
<script>
    document.querySelector('#REDIRECTINGS')
    .addEventListener('click' , () => {
        window.location.href = 'https://gamesforyou.co/sea-of-thieves-anniversary-edition-free-download/' ;
    })
</script><br><br>

<button id="REDIRECTS">VALORANT</button>
<script>
    document.querySelector('#REDIRECTS')
    .addEventListener('click' , () => {
        window.location.href = 'https://playvalorant.com/en-gb/';
    })
</script><br><br><br><br><br><br>

    <button id="direct">NEXT PAGE</button> 
    <script>
        document.querySelector('#direct')
        .addEventListener('click' , () => {
            window.location.href = 'file:///C:/Users/cly/Videos/coding/my%20first%20website/2page.html' ;
        });
    </script>
    </body>
</html>
