<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a6gbf1frc"/><path class="l14odab1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-sharp-fill" /></template>
<style>
.a6gbf1frc {
  fill: currentColor;
  d: path("M3 3L9 3L9 21L3 21L3 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l14odab1i {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM9 3L9 21M16.2929 8.7071L13 12L16.2929 15.2929");
}

</style>
