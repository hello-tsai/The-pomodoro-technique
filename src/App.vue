<template>
    <div id="app">
        <popup></popup>
        <time-title></time-title>
        <Time></Time>
    </div>
</template>

<script>
    import TimeTitle from "./components/TimeTitle";
    import Time from "./components/Time";
    import popup from "./components/common/popup";

    export default {
        components: {
            TimeTitle,
            Time,
            popup,
        }
    }
</script>

<style>
    @import "assets/styles/global.scss";

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;

        color: #2c3e50;
    }
</style>
