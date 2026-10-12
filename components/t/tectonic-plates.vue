<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it8mahb_z"/><path class="zv7o5cb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tectonic-plates" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it8mahb_z {
  d: path("M3.5 11.5h8.75q.75 0 .57.73l-1.14 4.54q-.18.73-.93.73H3.5q-.75 0-.75-.75v-4.5q0-.75.75-.75");
}

.zv7o5cb9x {
  d: path("M13.25 13.5h7.25q.75 0 .75.75v4.5q0 .75-.75.75h-8.75q-.75 0-.57-.73l1.14-4.54q.18-.73.93-.73m-9.75-7H9M7.25 4.75L9 6.5L7.25 8.25M20.5 6.5H15m1.75-1.75L15 6.5l1.75 1.75");
}

</style>
