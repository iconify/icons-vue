<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z2cqoi_za"/><path class="c0onh0bcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-pivot-sharp-duotone" /></template>
<style>
.c0onh0bcv {
  d: path("M20 12L20 20L12 20M17.7071 14.2929L20 12L22.2929 14.2929M14.2929 17.7071L12 20L14.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z2cqoi_za {
  stroke-opacity: 0.4;
  d: path("M2 8L20 8L20 2L2 2L2 20L8 20L8 8");
}

</style>
