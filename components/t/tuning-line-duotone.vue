<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q77o3mbpt"/><path class="b05_rogij"/><path class="t-oxy0bih"/><path class="yqmp105yd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-line-duotone" /></template>
<style>
.b05_rogij {
  d: path("M20 14.5C20 12.8431 18.6569 11.5 17 11.5C15.3431 11.5 14 12.8431 14 14.5C14 16.1569 15.3431 17.5 17 17.5C18.6569 17.5 20 16.1569 20 14.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q77o3mbpt {
  d: path("M10 9.5C10 11.1569 8.65685 12.5 7 12.5C5.34315 12.5 4 11.1569 4 9.5C4 7.84315 5.34315 6.5 7 6.5C8.65685 6.5 10 7.84315 10 9.5Z");
}

.t-oxy0bih {
  d: path("M17 11L17.0415 2M7 2V6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yqmp105yd {
  d: path("M7 13V22M17 22V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
