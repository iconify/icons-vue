<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u4yt2i7xs"/><path class="htcgw4bju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-stop-duotone" /></template>
<style>
.htcgw4bju {
  d: path("M9 11C9 9.895431 9.895431 9 11 9L13 9C14.104569 9 15 9.895431 15 11L15 13C15 14.104569 14.104569 15 13 15L11 15C9.895431 15 9 14.104569 9 13Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4yt2i7xs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.790861 3.790861 2 6 2L18 2C20.209139 2 22 3.790861 22 6L22 18C22 20.209139 20.209139 22 18 22L6 22C3.790861 22 2 20.209139 2 18Z");
  stroke: none;
}

</style>
