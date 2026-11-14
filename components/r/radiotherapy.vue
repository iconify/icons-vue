<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lhnxmhb1c"/><path class="ma3i6-6jf"/><path class="x355oor5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radiotherapy" /></template>
<style>
.lhnxmhb1c {
  d: path("m12 9.5l1.5 2.25l2.75.75V15l1.5 2.5l-3.25.75l-1.5 2.5l-2.5-1.5l-3.25-.5l.75-3L7.25 13l2.25-1Z");
}

.ma3i6-6jf {
  fill: currentColor;
  d: path("M10.75 14c1-.75 2.75-.5 3 .75c.25 1.5-.5 2.5-2 2.25c-1.25 0-1.75-2.25-1-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x355oor5l {
  d: path("m3 3l5 6.5m4-7v4.75M21 3l-5 6.5");
}

</style>
