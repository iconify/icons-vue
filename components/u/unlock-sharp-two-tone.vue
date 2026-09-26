<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m97iylbud"/><path class="yhggpq7zf"/><path class="k8te4qbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unlock-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k8te4qbon {
  fill: currentColor;
  d: path("M13.5 16C13.5 16.8284 12.8284 17.5 12 17.5C11.1716 17.5 10.5 16.8284 10.5 16C10.5 15.1716 11.1716 14.5 12 14.5C12.8284 14.5 13.5 15.1716 13.5 16Z");
  stroke: none;
}

.m97iylbud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10C3 9.4477 3.4477 9 4 9L20 9C20.5523 9 21 9.4477 21 10L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 10Z");
  stroke: none;
}

.yhggpq7zf {
  d: path("M16.5 10L16.5 6.5C16.5 4.0147 14.4853 2 12 2C9.5147 2 7.5 4.0147 7.5 6.5L7.5 7.5M4 10L4 22L20 22L20 10L4 10Z");
}

</style>
