<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gjsx1wbvw"/><path class="gjzfr7qea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-minus-sharp-duotone" /></template>
<style>
.gjsx1wbvw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.6189 13L12 13L12 21.618L10.5093 22.9514L4.2918 16C2.8159 14.3499 2 12.2138 2 10C2 5.0294 6.0294 1 11 1C15.9706 1 20 5.0294 20 10C20 10.7988 19.8909 11.5655 19.4644 13.2182Z");
  stroke: none;
}

.gjzfr7qea {
  d: path("M14 10C14 11.6569 12.6569 13 11 13C9.3431 13 8 11.6569 8 10C8 8.3431 9.3431 7 11 7C12.6569 7 14 8.3431 14 10ZM14 19L22 19");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
