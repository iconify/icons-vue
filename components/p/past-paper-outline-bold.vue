<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e0iy82b2q"/><path class="zy07-3bit"/><path class="za8zkd6ab"/><path class="oidvfgqrv"/><path class="i3ypschyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:past-paper-outline-bold" /></template>
<style>
.e0iy82b2q {
  d: path("M2 4a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.i3ypschyz {
  d: path("M5 15h5");
}

.oidvfgqrv {
  d: path("M5 11h9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.za8zkd6ab {
  d: path("M5 7h9");
}

.zy07-3bit {
  d: path("M6 21h15V6");
}

</style>
