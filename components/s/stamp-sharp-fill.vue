<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ayammnbbt"/><path class="tnrvpm1up"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stamp-sharp-fill" /></template>
<style>
.ayammnbbt {
  fill: currentColor;
  d: path("M15.1092 8.5165L15.769 11L21 11C21.5523 11 22 11.4477 22 12L22 17C22 17.5523 21.5523 18 21 18L3 18C2.4477 18 2 17.5523 2 17L2 12C2 11.4477 2.4477 11 3 11L8.231 11L8.8908 8.5165C8.3145 7.8044 8 6.9161 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6C16 6.9161 15.6855 7.8044 15.1092 8.5165Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tnrvpm1up {
  d: path("M4 21L20 21");
}

</style>
