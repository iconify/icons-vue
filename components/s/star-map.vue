<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5jmzt2ze"/><path class="t2gn4zr5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-map" /></template>
<style>
.h5jmzt2ze {
  d: path("m3.69 4.67l3.87-1.34q.94-.33 1.9-.06l5.08 1.46q.96.27 1.9-.06l3.87-1.34q.94-.33.94.67v14q0 1-.94 1.33l-3.87 1.34q-.94.33-1.9.06l-5.08-1.46q-.96-.27-1.9.06l-3.87 1.34q-.94.33-.94-.67V6q0-1 .94-1.33M8.5 5v4m0 6v2.5m7-10.5v2m0 6v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2gn4zr5b {
  d: path("M12 9.5q.3 2.2 2.5 2.5q-2.2.3-2.5 2.5q-.3-2.2-2.5-2.5q2.2-.3 2.5-2.5");
}

</style>
