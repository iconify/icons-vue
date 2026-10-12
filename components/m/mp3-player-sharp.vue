<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="p1xamwbmi"/><path class="g256l2bcj"/><circle class="biq2jjb5i"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mp3-player-sharp" /></template>
<style>
.biq2jjb5i {
  cx: 12px;
  cy: 15.75px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.g256l2bcj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.75h5.5v4.5h-6.5v-4.5z");
}

.p1xamwbmi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5v18.5H5.75z");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
