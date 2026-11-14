<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c66-hbb8h"/><path class="hyerbhbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-mower-boundary" /></template>
<style>
.c66-hbb8h {
  d: path("M3 7.5V5a2 2 0 0 1 2-2h2.5m2.75 0h3.5m2.75 0H19a2 2 0 0 1 2 2v2.5m0 2.75v3.5m0 2.75V19a2 2 0 0 1-2 2h-2.5m-2.75 0h-3.5M7.5 21H5a2 2 0 0 1-2-2v-2.5m0-2.75v-3.5M6.5 14a5.5 5 0 0 1 11 0Z");
}

.hyerbhbis {
  d: path("M7 15.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
