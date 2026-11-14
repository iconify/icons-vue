<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u_z66_1xv"/><path class="s_akglc9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seed-pod-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_akglc9i {
  d: path("M5.75 16.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10 12.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.25-3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M19.5 5.5L21 3");
}

.u_z66_1xv {
  d: path("M3.5 19.5c.5-10.25 5.75-15 16-14c-.5 10.25-5.75 15-16 14");
}

</style>
