<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="migxslb2k"/><path clip-rule="evenodd" class="wga-nlb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:semicolon-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.migxslb2k {
  d: path("M13 14C13 16 12 18 11 19L10.7071 19.2929");
}

.wga-nlb3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 6C14 7.1046 13.1046 8 12 8C10.8954 8 10 7.1046 10 6C10 4.8954 10.8954 4 12 4C13.1046 4 14 4.8954 14 6ZM14 14C14 15.1046 13.1046 16 12 16C10.8954 16 10 15.1046 10 14C10 12.8954 10.8954 12 12 12C13.1046 12 14 12.8954 14 14Z");
  stroke: none;
}

</style>
