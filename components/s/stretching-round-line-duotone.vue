<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xvkwtxc3k"/><path class="blm8jibri"/><path class="j5fz68bpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-round-line-duotone" /></template>
<style>
.blm8jibri {
  d: path("M7.94806 13.4346L7.92328 13.4106C6.88143 12.4038 7.6864 10.785 8.5932 10.1424C9.5 9.49992 13.3451 8.49992 13.3451 13.4343C13.3451 18.1287 9.69442 22 5 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5fz68bpz {
  d: path("M19.0004 21.9962V18.0492C19.0004 16.2733 17.3955 14.9201 15.627 15.205");
}

.xvkwtxc3k {
  cx: 14.5px;
  cy: 4.5px;
  r: 2.5px;
}

</style>
