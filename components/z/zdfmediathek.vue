<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rleb26osq"/><path class="petlldqnx"/><path class="nt3__rg0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zdfmediathek" /></template>
<style>
.nt3__rg0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.427 31.092a12.587 12.587 0 1 1 .57-13.264");
}

.petlldqnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.072 22.11a4.343 4.343 0 0 1 4.173-4.443a4.477 4.477 0 0 1 4.333 4.443a4.56 4.56 0 0 1-1.284 3.128c-1.765 1.481-7.222 5.76-7.222 5.76h8.506");
}

.rleb26osq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.37 17.831h5.295a6.586 6.586 0 0 1 0 13.167h-2.086m8.501-13.379h6.42m-6.42 6.583h4.173m-4.173-6.583v13.166");
}

</style>
