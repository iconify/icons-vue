<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mej7b4bsh"/><path class="k26tgublo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-message-two-tone" /></template>
<style>
.k26tgublo {
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM10 21L3 21C2.4477 21 2 20.5523 2 20C2 16.6863 4.6863 14 8 14L10 14M15 13L21 13C21.5523 13 22 13.4477 22 14L22 17C22 17.5523 21.5523 18 21 18L20 18L18 20.5L18 18L15 18C14.4477 18 14 17.5523 14 17L14 14C14 13.4477 14.4477 13 15 13Z");
}

.mej7b4bsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 13C10.5523 13 11 13.4477 11 14V21C11 21.5523 10.5523 22 10 22H3C1.89542 22 1 21.1046 1 20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
