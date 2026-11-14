<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="ox7pvcb5u"/><path class="sbkq1bcle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mask-background" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ox7pvcb5u {
  d: path("M15.5 5.938a7 7 0 0 1 0 12.124m-5.312.699a7 7 0 0 1-4.532-3.803m0-5.916a7 7 0 0 1 4.532-3.803M9.75 9.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.sbkq1bcle {
  d: path("M7.75 17.25c0-2 2-2.75 4.25-2.75s4.25.75 4.25 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
