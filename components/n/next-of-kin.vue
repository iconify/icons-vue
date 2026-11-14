<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="lezwx2b9d"/><path class="mka7r3b-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:next-of-kin" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.lezwx2b9d {
  d: path("M6 9.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4.75 16c0-1.75 1.5-2.75 3.25-2.75s3.25 1 3.25 2.75");
}

.mka7r3b-r {
  fill: currentColor;
  d: path("M16.5 15s-2.75-1.75-2.75-3.5c0-1 .75-1.75 1.5-1.75c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.75c0 1.75-2.75 3.5-2.75 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
