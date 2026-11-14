<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7n9d7pqd"/><path class="ufao-jbtb"/><path class="r41aysb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-terms" /></template>
<style>
.i7n9d7pqd {
  d: path("M7 2.5h7.5l5 5V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.r41aysb7q {
  d: path("M10 17.5c.25.5 1 .75 2 .75c1.25 0 2-.5 2-1.5c0-2.25-4-2.25-4-4.5c0-1 .5-1.5 1.5-1.75");
}

.ufao-jbtb {
  d: path("M14.5 2.5v5h5m-5.5 1c-.25-.5-1-.75-2-.75c-1.25 0-2 .5-2 1.5c0 2.25 4 2.25 4 4.5c0 1-.5 1.5-1.5 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
