<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hq-h8uxcp"/><path class="j9amvacjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:whiteboard-interview" /></template>
<style>
.hq-h8uxcp {
  d: path("M2.5 3.5h19v13h-19Z");
}

.j9amvacjb {
  d: path("m6.5 12.5l3-5l3 3.5l3-4.5l2 2.5M8 20.5l2.5-4m5.5 4l-2.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
