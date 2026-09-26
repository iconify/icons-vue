<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lpbvso84o"/><path class="lkq7fbn9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:receipt-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lkq7fbn9c {
  d: path("M7 9L13 9M7 13L17 13");
}

.lpbvso84o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 20C21 20.3788 20.786 20.725 20.4472 20.8944L16.4472 22.8944C16.1657 23.0352 15.8343 23.0352 15.5528 22.8944L12 21.118L8.4472 22.8944C8.1657 23.0352 7.8343 23.0352 7.5528 22.8944L3.5528 20.8944C3.214 20.725 3 20.3788 3 20L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
