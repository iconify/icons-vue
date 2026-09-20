<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rrwecdbui"/><path class="rp0qbo7xr"/><path class="m23phibpn"/><path class="g5nm6yyig"/><path class="ok9lcdcuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toll-booth-duotone-regular" /></template>
<style>
.g5nm6yyig {
  d: path("M20 12v9");
}

.m23phibpn {
  d: path("M9 12h13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ok9lcdcuh {
  d: path("M17 21h5");
}

.rp0qbo7xr {
  d: path("M3 21V8l3 -3 3 3v13Z");
}

.rrwecdbui {
  fill: currentColor;
  d: path("M3 21V8l3 -3 3 3v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
