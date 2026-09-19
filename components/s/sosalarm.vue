<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="jqui8kbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sosalarm" /></template>
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

.jqui8kbwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.636 32.205h8.097m-8.097-13.974l4.044-2.229m0 0v16.203m6.084-10.937a5.407 5.407 0 0 1 5.266-5.47a5.443 5.443 0 0 1 3.85 9.319c-2.229 1.823-9.113 7.09-9.113 7.09h10.739m-31.001-.002h8.1m-8.1-13.974l4.047-2.229m0 0v16.203");
}

</style>
