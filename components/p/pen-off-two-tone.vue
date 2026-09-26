<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ymwuqkrmm"/><path class="x5hmubb-n"/><path class="m7-i0ybpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-off-two-tone" /></template>
<style>
.m7-i0ybpu {
  d: path("M14.357 14.357L9.8567 18.8573L2 22L5.1427 14.1433L9.643 9.643M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5hmubb-n {
  stroke-opacity: 0.4;
  d: path("M17.1854 11.5286L21.0237 7.6904C21.6488 7.0652 22 6.2174 22 5.3333C22 4.4493 21.6488 3.6014 21.0237 2.9763C20.3986 2.3512 19.5507 2 18.6667 2C17.7826 2 16.9348 2.3512 16.3096 2.9763L12.4714 6.8146M15.0638 4.2222L19.7778 8.9362");
}

.ymwuqkrmm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.0641 15.0641L10.5639 19.5644C10.4681 19.6602 10.3539 19.7355 10.2281 19.7858L2.3714 22.9285C2.2533 22.9757 2.1272 23 2 23C1.4477 23 1 22.5523 1 22C1 21.8728 1.0243 21.7467 1.0715 21.6286L4.2142 13.7719C4.2645 13.6461 4.3398 13.5319 4.4356 13.4361L8.9359 8.9359Z");
  stroke: none;
}

</style>
