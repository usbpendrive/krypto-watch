<template>
  <header class="hero">
    <div class="bar logo">
      <h3>KryptoWatcher</h3>
      <span class="monitor"><span class="monitorText">receive updates</span></span>
    </div>
    <h1>Realtime PWA that displays updates on cryptocurrency.</h1>
    <h2>BitCoin, Ethereum, LiteCoin?</h2>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
header {
  background: linear-gradient(to bottom right, rgb(0, 193, 131), rgb(50, 72, 95));
  padding: 1em;
  margin-bottom: 1em;
  text-align: center;
  height: 300px;
  color: #fff;
}

header h3 {
  color: white;
  font-weight: bold;
  text-transform: uppercase;
  float: left;
}

.bar { padding: 20px; height: 48px;}
.monitor {
  text-transform: uppercase;
  float: right;
  background-color: rgba(255, 255, 255, 0.2);
  line-height: 23px;
  width: 175px;
  height: 48px;
  margin: auto;
}
.monitor:hover, .monitorText:hover { cursor: pointer; }
.monitorText {
  width: 104px;
  height: 23px;
  font-weight: bold;
  line-height: 50px;
  font-size: 24px;
}
header h1 { padding-top: 80px; width: 80%; margin: auto; }
header h2 { padding-top: 20px; }
</style>
