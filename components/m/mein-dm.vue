<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kcw7jzb1t"/><path class="da_o_ubon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mein-dm" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.da_o_ubon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.328 32.522c-5.351-1.552-10.7-3.008-15.92.05");
}

.kcw7jzb1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.28 20.593a3.104 3.104 0 0 1 3.104-3.104h0a3.104 3.104 0 0 1 3.104 3.104v5.122m-6.209-8.226v8.226m6.209-5.122a3.104 3.104 0 0 1 3.104-3.104h0a3.104 3.104 0 0 1 3.104 3.104v5.122m-15.71-5.032a3.104 3.104 0 0 0-3.104-3.105h0a3.104 3.104 0 0 0-3.105 3.105V22.7a3.104 3.104 0 0 0 3.105 3.104h0a3.104 3.104 0 0 0 3.104-3.104m0 3.104V13.388M8.383 29.492c15.121-6.777 18.293 7.236 31.89 1.742m-1.666-3.156c-4.082 1.46-9.192 1.027-16.059-.963");
}

</style>
