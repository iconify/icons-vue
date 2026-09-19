<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xw4-skb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marks-and-spencer" /></template>
<style>
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

.xw4-skb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.674 27.991V20l4 8l4-7.988V28m13.51-.876c.49.639 1.106.877 1.962.877h1.184a1.996 1.996 0 0 0 1.996-1.996v-.009A1.996 1.996 0 0 0 35.33 24h-1.307a2 2 0 0 1-1.997-1.997c0-1.106.896-2.003 2.002-2.003h1.178c.855 0 1.47.238 1.961.877M28.777 28h-.676a1.4 1.4 0 0 1-1.132-.576l-2.775-3.815c-.356-.468-.984-1.084-.984-1.997c0-.862.7-1.612 1.675-1.612a1.6 1.6 0 0 1 1.62 1.612c0 .913-.739 1.693-2.106 1.953c-1.524.289-2.477 1.125-2.477 2.503c0 1.115.703 1.932 2.107 1.932c1.847 0 2.933-1.75 4.538-3.902");
}

</style>
