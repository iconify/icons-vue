<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="shm12v81x"/><path class="wrbkd_brp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-play" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.shm12v81x {
  d: path("M7 6h10a2.5 2.5 0 0 1 2.5 2.5v7A2.5 2.5 0 0 1 17 18h-2a3 2 0 0 0-6 0H7a2.5 2.5 0 0 1-2.5-2.5v-7A2.5 2.5 0 0 1 7 6m-4.5 5.5h2m15 0h2");
}

.wrbkd_brp {
  d: path("m12.185 9.714l.065.036a1.43 1.43 0 0 1 0 2.5l-.065.036A1.47 1.47 0 0 1 10 11a1.47 1.47 0 0 1 2.185-1.286");
}

</style>
