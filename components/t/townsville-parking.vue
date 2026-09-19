<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="mjs7qacam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:townsville-parking" /></template>
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

.mjs7qacam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.7 30.3V35m-19 0v-4.7h1.5c.9 0 1.6.7 1.6 1.6s-.7 1.6-1.6 1.6H9.7M19 35v-4.7h1.5c.9 0 1.6.7 1.6 1.6s-.7 1.6-1.6 1.6H19m1.6 0l1.5 1.5M8.6 12.7h8.7M13 25.8V12.7M31.2 35v-4.7l3.1 4.7v-4.7m5.1-17.6L35 25.8l-4.3-13.1M19.6 24.3c.8 1 1.8 1.4 3.2 1.4h1.9c1.8 0 3.3-1.5 3.3-3.3h0c0-1.8-1.5-3.3-3.3-3.3h-2.1c-1.8 0-3.3-1.5-3.3-3.3h0c0-1.8 1.5-3.3 3.3-3.3h1.9c1.4 0 2.4.4 3.2 1.4m11.7 18c0-.9-.7-1.6-1.6-1.6h0c-.9 0-1.6.7-1.6 1.6v1.6c0 .9.7 1.6 1.6 1.6h0c.9 0 1.6-.7 1.6-1.6h-1.6m-21.3 0h-2.1m-.5 1.5l1.5-4.7L17 35m7.1-4.7V35m0-1.6l2.5-3m0 4.6l-1.9-2.3");
}

</style>
