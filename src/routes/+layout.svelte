<script>
	let { children } = $props();
</script>

<!-- <div id = "banner">

</div> -->




<style>
    #main{
        background-color: black;
    }
    .banner{
        position: fixed;
        background-color: black;
        
    }
    h1{
        font-family: Voltaire;
    } 
    p{
        font-family: Garet;
    }
    @font-face{
        font-family: 'Voltaire';
        font-style: normal;
        font-weight: 400;
        src: url('/static/fonts/Voltaire-Frangela.ttf') format('truetype');
    }
    @font-face{
        font-family: 'Garet';
        font-style: normal;
        font-weight: 300;
        src: url('/static/fonts/Garet-Book.ttf') format('truetype');
    }
</style>

{@render children()}