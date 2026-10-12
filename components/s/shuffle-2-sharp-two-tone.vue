<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="aziicjvmz"/><path class="lb3terykh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-2-sharp-two-tone" /></template>
<style>
.aziicjvmz {
  stroke-opacity: 0.4;
  d: path("M2.7071 2.7071L9.8787 9.8787M14.1213 14.1213L20.8243 20.8243M14 21L21 21L21 14");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lb3terykh {
  d: path("M2.7071 21.2929L20.8243 3.1757M14 3L21 3L21 10");
}

</style>
