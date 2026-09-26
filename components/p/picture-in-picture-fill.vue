<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="siwcx2s2t"/><path class="u0bo7s5iv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:picture-in-picture-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.siwcx2s2t {
  fill: currentColor;
  d: path("M14 11L20 11C21.65685 11 23 12.34315 23 14L23 18C23 19.65685 21.65685 21 20 21L14 21C12.34315 21 11 19.65685 11 18L11 14C11 12.34315 12.34315 11 14 11Z");
  stroke: none;
}

.u0bo7s5iv {
  d: path("M22 8V7C22 5.34315 20.65685 4 19 4H5C3.34315 4 2 5.34315 2 7V17C2 18.65685 3.34315 20 5 20H8");
}

</style>
