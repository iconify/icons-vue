<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lktavab9z"/><path class="xjkr4fb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater-duocolor" /></template>
<style>
.lktavab9z {
  stroke-opacity: 0.4;
  d: path("M13.336 7.208h.01m3.929-.695h.01m-3.428 3.65a2.267 2.267 0 0 0 3.939-.695M6.725 11.713h.01m-.705 3.94a2.267 2.267 0 0 1 3.94.694");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xjkr4fb1c {
  d: path("m11.076 11.668l-.868-4.924a2 2 0 0 1 1.622-2.317l5.909-1.042a2 2 0 0 1 2.317 1.623l.868 4.924a5 5 0 0 1-9.848 1.736m1.495 6.36a5.002 5.002 0 0 1-9.495-2.896l.868-4.924a2 2 0 0 1 2.317-1.623l1.264.223");
}

</style>
