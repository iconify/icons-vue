<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t9_psxdfo"/><path class="gv69jht3v"/><path class="sz0grsbiu"/><path class="gq2dgkb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:train-clock-sharp" /></template>
<style>
.gq2dgkb4a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 17.25l-2.25 4m8.75-4l2.25 4");
}

.gv69jht3v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5.5h8.5V10h-8.5z");
}

.sz0grsbiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 13.75h.01m6.49 0h.01");
}

.t9_psxdfo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v14.5H5.25z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
