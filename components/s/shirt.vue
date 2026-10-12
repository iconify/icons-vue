<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vp0gj2eyt"/><path class="v3eonzbdl"/><path class="yxl_vybyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shirt" /></template>
<style>
.v3eonzbdl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.83 3.63l2.84 3.24q.33.38-.02.73L10.1 9.15q-.35.35-.59-.09L7.49 5.44q-.24-.44.05-.85l.67-.93q.29-.41.62-.03m6.34 0l-2.84 3.24q-.33.38.02.73l1.55 1.55q.35.35.59-.09l2.02-3.62q.24-.44-.05-.85l-.67-.93q-.29-.41-.62-.03");
}

.vp0gj2eyt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.25h5q1 0 1.89.45l2.72 1.35q.89.45 1.05 1.44l.93 5.52q.16.99-.71 1.24q-.88.25-1.33-.64l-.85-1.72q-.45-.89-.45.11v8.75q0 1-1 1h-9.5q-1 0-1-1V11q0-1-.45-.11l-.85 1.72q-.45.89-1.32.64q-.88-.25-.72-1.24l.93-5.52Q4 5.5 4.89 5.05L7.61 3.7q.89-.45 1.89-.45");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yxl_vybyn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.5h.01M12 16.25h.01");
}

</style>
