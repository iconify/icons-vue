<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skssyspmt"/><path class="sif23b_uv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wing-mirror" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sif23b_uv {
  d: path("m6.74 8.13l5.02-.51q1.24-.12 1.3 1.13l.13 3Q13.25 13 12 13.09l-4.5.32q-1.25.09-1.43-1.15l-.39-2.77Q5.5 8.25 6.74 8.13m10.11 3.9l3.55 2.19q.85.53.85 1.53v4.5q0 1-1 1h-.75q-1 0-1.53-.85l-1.94-3.05q-.53-.85-.43-1.85l.3-3q.1-1 .95-.47");
}

.skssyspmt {
  d: path("m5.24 5.74l7.02-.73q2.49-.26 3.24 1.87q.75 2.12.56 4.61l-.12 1.52q-.19 2.49-2.69 2.6l-6.5.28q-2.5.11-2.87-2.36l-.76-5.06Q2.75 6 5.24 5.74");
}

</style>
