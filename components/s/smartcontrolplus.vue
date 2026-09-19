<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="mlqljbc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartcontrolplus" /></template>
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

.mlqljbc4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 39.5c2.2 0 4.2-.8 6-2c1.6-1.2 2.9-2.7 3.8-4.5s1.7-3.6 2.2-5.5c.7-2.3 1.1-4.7 2-7c.8-2.3 2.2-4.4 4-6c1.7-1.3 3.8-2 6-2m-39 23c2.2 0 4.2-.8 6-2c1.6-1.2 2.9-2.7 3.8-4.5s1.7-3.6 2.2-5.5c.7-2.3 1.1-4.7 2-7c.8-2.3 2.2-4.4 4-6c1.7-1.3 3.8-2 6-2m8.5 21v7M33.5 33h7");
}

</style>
