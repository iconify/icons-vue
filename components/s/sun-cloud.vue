<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcqjucchp"/><path class="wi724cc1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun-cloud" /></template>
<style>
.fcqjucchp {
  d: path("M9 20.5a3.5 3.5 0 0 1 0-7a5 5 0 0 1 9.5.5a3.5 3.5 0 0 1 0 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wi724cc1x {
  d: path("M12.25 10.5a3 3 0 1 0-2.75 2m0-8.75V2M3.75 9.5H2m3.5-4L4.25 4.25M13.5 5.5l1.25-1.25");
}

</style>
