<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="r7hvp0biu"/><path class="gpa9x7bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:materialistic" /></template>
<style>
.gpa9x7bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.236 16.543l1.714-2.967l1.713 2.967m.001 2.403l-1.714 2.969l-1.714-2.969m0 10.088l1.714-2.967l1.713 2.967m.001 2.403l-1.714 2.969l-1.714-2.969m7.687-17.861h21.11m-.001 4.169H21.648m3.725 4.17h13.66m-21.11 4.17h21.11m-.001 4.17H21.648m3.725 4.169h13.66");
}

.r7hvp0biu {
  width: 39px;
  height: 31.2px;
  x: 4.5px;
  y: 8.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
