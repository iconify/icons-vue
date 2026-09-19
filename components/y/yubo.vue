<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="js6jtabyd"/><path class="pfa46nius"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yubo" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.js6jtabyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.999 25.522l23.425-7.24a12.37 12.37 0 0 1-.216 8.097a12.37 12.37 0 0 1-5.218 6.195c-3.193 1.888-7.262 2.216-10.715.862s-6.217-4.359-7.276-7.914");
}

.pfa46nius {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 32.174q.063-.439.182-.866a7 7 0 0 1 .778-1.776c.67-1.081 1.646-1.958 2.748-2.593a9.2 9.2 0 0 1 5.047-1.206m0 0a6.9 6.9 0 0 1-.96 2.63c-.67 1.08-1.646 1.957-2.748 2.592A9.26 9.26 0 0 1 24 32.175");
}

</style>
