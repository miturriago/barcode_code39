<template>
<barcode :value="value" :tag="tag"  :options="options"></barcode>

</template>
<script>
export default {
 data () {
    return {
        value: 'TEST',
        tag: 'svg',
        options: {
            lineColor: '#ff7069',
            fontSize: 32,
            font: 'Courier',
            width: 3,
            height: 60,
            marginBottom: 60,
            format: 'CODE 39',
            background: '#ccffff'
        },
    }
}
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
