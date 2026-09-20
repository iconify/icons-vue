<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l3dxtabwt"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tdsb-connects" /></template>
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

.l3dxtabwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.283 28.04c.518.435 1.077.635 2.333.635h.637a1.88 1.88 0 0 0 1.876-1.88c0-1.038-.84-1.88-1.876-1.88H25.98a1.88 1.88 0 0 1-1.876-1.88c0-1.038.84-1.88 1.876-1.88h.637c1.256 0 1.815.2 2.333.635m-16.96-2.975v8.441c0 .784.635 1.419 1.418 1.419h.426M10.5 21.156h2.979m7.998 2.837a2.837 2.837 0 1 0-5.675 0v1.844a2.837 2.837 0 1 0 5.675 0m0 2.838v-11.35m10.348 6.668a2.837 2.837 0 1 1 5.675 0v1.844a2.837 2.837 0 1 1-5.675 0m0 2.838v-11.35");
}

</style>
