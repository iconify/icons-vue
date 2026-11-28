<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ugpv1f8sh"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

.ugpv1f8sh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 6V13C6.552 13 7 13.448 7 14V20C7 20.552 6.552 21 6 21H2C1.448 21 1 20.552 1 20V4C1 3.448 1.448 3 2 3H3L6 6ZM21 21H10C9.448 21 9 20.552 9 20V14C9 13.448 9.448 13 10 13V10L21 21ZM6.657 3H12H22C22.552 3 23 3.448 23 4V19.343L16.657 13H18V5H14V10.343L6.657 3Z");
  stroke: none;
}

</style>
