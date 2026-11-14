<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slso21bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seed-sowing" /></template>
<style>
.slso21bnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H11c2.5 0 4 1 5.5 2.75L18 8c.75 1 .25 2-1 2h-4.5l.5 2.25c.25 1-.5 1.75-1.5 1.25l-3.5-2H2.5m0 9.5h19m-11-14.25H15m3 6.5h.01M15 16.5h.01m4.49 1.25h.01");
}

</style>
