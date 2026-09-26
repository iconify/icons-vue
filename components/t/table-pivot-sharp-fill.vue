<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="shak1in_o"/><path class="a_5ofobug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-pivot-sharp-fill" /></template>
<style>
.a_5ofobug {
  d: path("M2 8L20 8L20 2L2 2L2 20L8 20L8 8M20 12L20 20L12 20M17.7071 14.2929L20 12L22.2929 14.2929M14.2929 17.7071L12 20L14.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shak1in_o {
  fill: currentColor;
  d: path("M2 8L8 8L8 20L2 20L2 8Z");
  stroke: none;
}

</style>
