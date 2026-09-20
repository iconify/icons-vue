<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x15-b37rj"/><path class="m8-ejfrzs"/><path class="c4my-jbpv"/><path class="qkea2dbiu"/><path class="y5ppprd7z"/><path class="ojrtcibbk"/><path class="af7-lid5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:query-timeout-duotone-bold" /></template>
<style>
.af7-lid5z {
  d: path("M12 16.5h4");
}

.c4my-jbpv {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.m8-ejfrzs {
  fill: currentColor;
  d: path("M7 16.5a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ojrtcibbk {
  d: path("M12 12.5v4");
}

.qkea2dbiu {
  d: path("M5 6.5h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x15-b37rj {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y5ppprd7z {
  d: path("M7 16.5a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
