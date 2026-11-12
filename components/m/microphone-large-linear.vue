<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bg1voxbrd"/><path class="fvun-abzf"/><path class="c_apmbcjm"/><path class="hq35snb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-large-linear" /></template>
<style>
.bg1voxbrd {
  d: path("M12 19C8.68629 19 6 16.3137 6 13V8C6 4.68629 8.68629 2 12 2C15.3137 2 18 4.68629 18 8V13C18 16.3137 15.3137 19 12 19Z");
}

.c_apmbcjm {
  d: path("M10 9.5C10 9.5 10.4727 9 12 9C13.5273 9 14 9.5 14 9.5");
}

.fvun-abzf {
  d: path("M10 6.5C10 6.5 10.4727 6 12 6C13.5273 6 14 6.5 14 6.5");
}

.hq35snb1x {
  d: path("M21 11V13C21 17.9706 16.9706 22 12 22C7.02944 22 3 17.9706 3 13V11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
