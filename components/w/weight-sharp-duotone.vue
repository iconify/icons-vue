<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="shrye9wgc"/><path class="na-4ufbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:weight-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.na-4ufbnj {
  fill: currentColor;
  d: path("M7 8L17 8C17.4304 8 17.8126 8.2754 17.9487 8.6838L21.9487 20.6838C21.9827 20.7857 22 20.8925 22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21C2 20.8925 2.0173 20.7857 2.0513 20.6838L6.0513 8.6838C6.1874 8.2754 6.5696 8 7 8Z");
  stroke: none;
}

.shrye9wgc {
  stroke-opacity: 0.4;
  d: path("M15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6Z");
}

</style>
