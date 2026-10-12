<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f6cxlrkdq"/><path class="f3iw4acio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:studio-mic-sharp" /></template>
<style>
.f3iw4acio {
  d: path("M4.75 10.75a7.25 7.25 0 0 0 14.5 0M12 18v3.25");
}

.f6cxlrkdq {
  d: path("M8.25 2.75h7.5v11.5h-7.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
