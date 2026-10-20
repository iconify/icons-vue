<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v3tkdybcd"/><path class="h4ellt4wt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:planet-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h4ellt4wt {
  d: path("M5.0002 12.0505C2.8253 13.4478 1.7403 14.762 2.0528 15.6205C2.6195 17.1774 7.5324 16.8186 13.0261 14.8191C18.5198 12.8195 22.5139 9.9364 21.9472 8.3795C21.6347 7.521 19.9589 7.2117 17.3946 7.5393");
}

.v3tkdybcd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 12C20 16.4183 16.4183 20 12 20C7.5817 20 4 16.4183 4 12C4 7.5817 7.5817 4 12 4C16.4183 4 20 7.5817 20 12Z");
  stroke: none;
}

</style>
