<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u4d8or8je"/><path class="w8slmsefx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-alert-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4d8or8je {
  d: path("M2 6.8477L12 12M12 12L22 6.8477M7 4.4239L17 9.4239M12 12L12 22L2 17.1523L2 6.8477L12 2L22 6.8477L22 13M19 15L19 19");
}

.w8slmsefx {
  fill: currentColor;
  d: path("M20 22C20 22.5523 19.5523 23 19 23C18.4477 23 18 22.5523 18 22C18 21.4477 18.4477 21 19 21C19.5523 21 20 21.4477 20 22Z");
  stroke: none;
}

</style>
