<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ek-enmbac"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sns-bank" /></template>
<style>
.ek-enmbac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.953 28.6v-9.2l6.094 9.2v-9.2m-14.365 8.192c.564.734 1.272 1.008 2.256 1.008H16.3a2.295 2.295 0 0 0 2.295-2.295v-.01A2.295 2.295 0 0 0 16.3 24h-1.503a2.297 2.297 0 0 1-2.297-2.297a2.3 2.3 0 0 1 2.302-2.303h1.355c.984 0 1.691.274 2.256 1.008m11.175 7.184c.564.734 1.271 1.008 2.255 1.008h1.362a2.295 2.295 0 0 0 2.295-2.295v-.01A2.295 2.295 0 0 0 33.205 24h-1.502a2.297 2.297 0 0 1-2.298-2.297a2.3 2.3 0 0 1 2.303-2.303h1.354c.984 0 1.692.274 2.256 1.008");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
