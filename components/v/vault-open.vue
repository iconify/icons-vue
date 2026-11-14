<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt1p1tbue"/><path class="cny0lyb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vault-open" /></template>
<style>
.cny0lyb1c {
  d: path("M4 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m10.25-3.25h2m-2 6.5h2m1.5-3.25a1 2.75 0 1 0 2 0a1 2.75 0 1 0-2 0m-.5 0h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yt1p1tbue {
  d: path("M2 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m14 0a2.75 8.5 0 1 0 5.5 0a2.75 8.5 0 1 0-5.5 0");
}

</style>
