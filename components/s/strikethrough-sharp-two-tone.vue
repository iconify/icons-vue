<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ytl30t-br"/><path class="pn7hvrb-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:strikethrough-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pn7hvrb-k {
  d: path("M8 9L8 8C8 5.7909 9.7909 4 12 4C13.1093 4 14.1689 4.4607 14.9254 5.272L15.222 5.59");
}

.ytl30t-br {
  stroke-opacity: 0.4;
  d: path("M12 12C14.2091 12 16 13.7909 16 16C16 18.2091 14.2091 20 12 20C10.3184 20 8.8164 18.9483 8.2412 17.3681L8.0017 16.7101M2 12L22 12");
}

</style>
