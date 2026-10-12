<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nl3p61b-q"/><path class="jjd86ybbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:metronome-sharp" /></template>
<style>
.jjd86ybbk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.15 10.5h.01");
}

.nl3p61b-q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h4l.35 1.46l3.8 15.58l.35 1.46H4.75l.35-1.46L8.9 4.21l.35-1.46zm-3.5 14.5h9.5m-4.75 0l1.5-8.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
