<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5u692bhg"/><path class="mq608-1pz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-branch-visit-reason" /></template>
<style>
.mq608-1pz {
  d: path("M10.25 9.25c0-1.25.75-2 1.75-2S13.75 8 13.75 9c0 1.5-1.75 1.75-1.75 3.25m0 3.25h.01");
}

.q5u692bhg {
  d: path("M3 4.5h18V10a2 2 0 0 0 0 4v5.5H3V14a2 2 0 0 0 0-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
