<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a27qx-bgt"/><path class="v8p95uwfi"/><path class="xiwl7qbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-360" /></template>
<style>
.a27qx-bgt {
  d: path("M9 3h6a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 15 13H9a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 9 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8p95uwfi {
  d: path("M12.375 6.875za1.312 1.312 0 0 1 0 2.25A1.238 1.238 0 0 1 10.5 8.063v-.126a1.238 1.238 0 0 1 1.875-1.062M2.5 12c0 4.5 4.5 8 9.5 8c3.25 0 6.5-1.5 8.5-4");
}

.xiwl7qbno {
  d: path("m17.75 16.5l2.75-.5l.25 2.75");
}

</style>
