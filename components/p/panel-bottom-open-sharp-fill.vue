<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pl-jx2b0v"/><path class="y0ssgbcbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pl-jx2b0v {
  fill: currentColor;
  d: path("M3 15L21 15L21 21L3 21L3 15Z");
  stroke: none;
}

.y0ssgbcbf {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 15L21 15M8.7071 11.2929L12 8L15.2929 11.2929");
}

</style>
