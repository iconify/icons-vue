<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iji8pn0_v"/><path class="z5b_ktbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:winery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iji8pn0_v {
  d: path("M13.433 20.5H3v-11l9-6l9 6v1.767");
}

.z5b_ktbrl {
  d: path("M7 20.5V16a2 2 0 0 1 4 0v4.5m4.5-6.5h5v1a2.5 2.5 0 0 1-5 0Zm2.5 3.5v3.25m-1.75 0h3.5");
}

</style>
