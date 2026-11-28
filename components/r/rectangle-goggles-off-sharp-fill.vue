<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="em_f81bnt"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.em_f81bnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 19L16 19C15.6962 19 15.4089 18.8619 15.2191 18.6247L12 14.6008L8.7809 18.6247C8.5911 18.8619 8.3038 19 8 19L2 19C1.4477 19 1 18.5523 1 18L1 6C1 5.4477 1.4477 5 2 5L5 5ZM8.6569 5L12 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23 18.3641 22.8054 18.6828 22.5145 18.8576Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
