<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="z13ah3brv"/><path class="p-1h55b8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squat-rack-sharp" /></template>
<style>
.p-1h55b8k {
  d: path("M2.75 9.25h18.5M4.5 7v4.5m15-4.5v4.5m-7.25-.75L7.5 14.5h7l-1.75 6.75h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z13ah3brv {
  cx: 13px;
  cy: 4.5px;
  r: 1.75px;
}

</style>
