<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b0uytfbhh"/><path class="qsaekxsjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:siem-dashboard-sharp" /></template>
<style>
.b0uytfbhh {
  d: path("M2.75 3.25h18.5v13.5H2.75zM12 16.75v4.5m-3.5 0h7");
}

.qsaekxsjb {
  d: path("m6 12.5l3-3.25l2.5 2l3-4l3.5 3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
