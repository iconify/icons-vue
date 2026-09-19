<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ydtfb2bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tapa" /></template>
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

.ydtfb2bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.374 18.376l-1.578 6.935c-.147.644.252 1.166.891 1.166h.348m-1.314-6.178h2.43m6.588 3.847c-.293 1.288-1.567 2.331-2.845 2.331s-2.077-1.044-1.784-2.331l.345-1.515c.293-1.288 1.567-2.331 2.845-2.331s2.077 1.043 1.784 2.33m-.875 3.847l1.406-6.178m13.473 3.847c-.293 1.288-1.567 2.331-2.845 2.331s-2.077-1.044-1.784-2.331l.345-1.515c.293-1.288 1.567-2.331 2.845-2.331s2.077 1.043 1.784 2.33m-.875 3.847l1.406-6.178m-12.679 3.847c-.293 1.288.506 2.331 1.784 2.331s2.552-1.044 2.845-2.331l.345-1.515c.293-1.288-.506-2.331-1.784-2.331s-2.552 1.043-2.845 2.33m.531-2.331l-2.123 9.325");
}

</style>
