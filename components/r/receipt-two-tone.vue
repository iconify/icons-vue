<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzp6wqb3w"/><path class="spsvkm9ev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:receipt-two-tone" /></template>
<style>
.mzp6wqb3w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5C3 2.79086 4.79086 1 7 1H17C19.2091 1 21 2.79086 21 5V20C21 20.3788 20.786 20.725 20.4472 20.8944L16.4472 22.8944C16.1657 23.0352 15.8343 23.0352 15.5528 22.8944L12 21.118L8.44721 22.8944C8.16569 23.0352 7.83431 23.0352 7.55279 22.8944L3.55279 20.8944C3.214 20.725 3 20.3788 3 20V5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.spsvkm9ev {
  d: path("M8 9H12M8 13H16M4 5C4 3.34315 5.34315 2 7 2H17C18.6569 2 20 3.34315 20 5V20L16 22L12 20L8 22L4 20V5Z");
}

</style>
