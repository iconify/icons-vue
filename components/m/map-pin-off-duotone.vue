<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t41omzb7x"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t41omzb7x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.4296 17.4296L12.75 22.6667C12.5556 22.8788 12.2846 23 12 23C11.7154 23 11.4444 22.8788 11.2546 22.6667L5.2918 16C3.8159 14.35 3 12.2138 3 10C3 8.03 3.6361 6.1987 4.7146 4.7146L17.4296 17.4296ZM7.7668 3.5241C7.54 3.296 7.4346 2.9719 7.4873 2.6536C7.54 2.3354 7.743 2.0621 8.03 1.9197C9.2293 1.3307 10.576 1 12 1C16.9706 1 21 5.0294 21 10C21 11.3856 20.6804 12.74 20.0793 13.9654C19.9371 14.2551 19.6638 14.46 19.3454 14.5113C19.027 14.5642 18.7027 14.46 18.4745 14.2319L14.2427 10C14.2427 8.7614 13.2386 7.7573 12 7.7573L7.7668 3.5241Z");
  stroke: none;
}

</style>
