<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u01a_kvvb"/><path class="hq8c060ps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whiskey-glass-sharp" /></template>
<style>
.hq8c060ps {
  d: path("m10.72 9.25l2.81.75l.97.25l-.25.97l-.75 2.81l-.25.97l-.97-.25L9.47 14l-.97-.25l.25-.97l.75-2.81l.25-.97zM7 18h10");
}

.u01a_kvvb {
  d: path("M3.75 5.75h16.5L19 19.25l-.222 1.764L17 21H7l-1.778.014L5 19.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
