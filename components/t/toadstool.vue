<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n-_sref2c"/><path class="zxts1xnci"/><path class="tqu9e0byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toadstool" /></template>
<style>
.n-_sref2c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11C2.75 7.25 7 4.25 12 4.25s9.25 3 9.25 6.75c0 .75-.5 1.25-1.25 1.25H4c-.75 0-1.25-.5-1.25-1.25");
}

.tqu9e0byo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12.25h3l.25 5.25c1.25.5 2 1.5 2 2.5c0 .75-.5 1.25-1.25 1.25h-5c-.75 0-1.25-.5-1.25-1.25c0-1 .75-2 2-2.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxts1xnci {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9.25h.01m4.99-2h.01m4.99 2h.01");
}

</style>
