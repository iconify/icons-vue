<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5lvicvhn"/><path class="w1pb88qcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-radical-two-tone" /></template>
<style>
.i5lvicvhn {
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 4.3431 4.3431 3 6 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w1pb88qcg {
  d: path("M7.3125 12.9375L8.2267 12.328C8.4841 12.1564 8.834 12.2574 8.9604 12.5397L10.2367 15.3902C10.4308 15.8237 11.0633 15.7677 11.1782 15.3068L12.843 8.629C12.8985 8.4063 13.0986 8.25 13.3282 8.25L16.6875 8.25");
}

</style>
