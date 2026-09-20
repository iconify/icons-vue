<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o5r_prbgx"/><path class="xrw775b-m"/><path class="el8_zutrb"/><path class="wc07w8blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:noise-schedule-outline-regular" /></template>
<style>
.el8_zutrb {
  d: path("M16 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5r_prbgx {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wc07w8blj {
  d: path("M20 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xrw775b-m {
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
