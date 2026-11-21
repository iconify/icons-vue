<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i_2jq7bdt"/><path class="qj1m6tb2o"/><path class="hr4ikch1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-sparkle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hr4ikch1o {
  d: path("M12 6.0006L14.1469 9.8531L17.9994 12L14.1469 14.1469L12 17.9994L9.8531 14.1469L6.0006 12L9.8531 9.8531Z");
}

.i_2jq7bdt {
  stroke-opacity: 0.4;
  d: path("M3 9L3 8L3 3L8 3L9 3M15 3L16 3L21 3L21 8L21 9M21 15L21 16L21 21L16 21L15 21M9 21L8 21L3 21L3 16L3 15");
}

.qj1m6tb2o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.5599 10.053L18.4862 11.1265C18.803 11.303 18.9994 11.6373 18.9994 12C18.9994 12.3627 18.803 12.697 18.4862 12.8735L14.882 14.882L12.8735 18.4862C12.697 18.803 12.3627 18.9994 12 18.9994C11.6373 18.9994 11.303 18.803 11.1265 18.4862L9.118 14.882L5.5138 12.8735C5.197 12.697 5.0006 12.3627 5.0006 12C5.0006 11.6373 5.197 11.303 5.5138 11.1265L9.118 9.118L11.1265 5.5138C11.303 5.197 11.6373 5.0006 12 5.0006C12.3627 5.0006 12.697 5.197 12.8735 5.5138L14.882 9.118Z");
  stroke: none;
}

</style>
