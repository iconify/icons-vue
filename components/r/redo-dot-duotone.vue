<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sis4014_e"/><path class="pelh9kbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-dot-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pelh9kbkx {
  fill: currentColor;
  d: path("M11.2851 16.9998C11.2851 18.1044 12.1805 18.9998 13.2851 18.9998C14.3897 18.9998 15.2851 18.1044 15.2851 16.9998C15.2851 15.8952 14.3897 14.9998 13.2851 14.9998C12.1805 14.9998 11.2851 15.8952 11.2851 16.9998Z");
  stroke: none;
}

.sis4014_e {
  stroke-opacity: 0.4;
  d: path("M3 17.9998C3 13.9534 5.3726 10.283 9.0622 8.6216C12.7518 6.9602 17.0727 7.6166 20.1025 10.2987M21 6.0002V11H16");
}

</style>
