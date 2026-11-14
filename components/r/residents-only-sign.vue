<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdq7e0nga"/><path class="f0-1fctms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:residents-only-sign" /></template>
<style>
.f0-1fctms {
  d: path("M7 13V8.5l5-3.25l5 3.25V13Z");
}

.jdq7e0nga {
  d: path("M3 2.5h18V16H3ZM12 16v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
