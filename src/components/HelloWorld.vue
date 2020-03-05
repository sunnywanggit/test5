<template>
    <div class="hello">
        <g-button>second push</g-button>
    </div>
</template>

<script>
    import {Button} from 'sunny-wheel'
    import 'sunny-wheel/dist/index.css'

    export default {
        components: {
            'g-button': Button
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    :root {
        --button-height: 32px;
        --font-size: 14px;
        --button-bg: white;
        --button-active-bg: #eee;
        --button-radius: 4px;
        --color: #333;
        --border-color: #999;
        --border-color-hover: #666;
    }
    h3 {
        margin: 40px 0 0;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }
</style>
