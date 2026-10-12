<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gf5ll8r0l"/><circle class="obsscdhly"/><path class="s5cxhbcmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reach-eye-sharp" /></template>
<style>
.gf5ll8r0l {
  d: path("M4.25 14C6 11 8.75 9.25 12 9.25S18 11 19.75 14c-1.75 3-4.5 4.75-7.75 4.75S6 17 4.25 14Z");
}

.obsscdhly {
  cx: 12px;
  cy: 14px;
  r: 2px;
}

.s5cxhbcmn {
  d: path("M9 7.5a7 7 0 0 1 6 0M6.5 5.25a11 11 0 0 1 11 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
