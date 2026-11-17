<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wvvmb4bsf"/><path class="fudwqibmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-split-bottom-right-sharp-fill" /></template>
<style>
.fudwqibmg {
  d: path("M12 21V12H21M3 3H21V21H3V3Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wvvmb4bsf {
  fill: currentColor;
  d: path("M12 12H21V21H12V12Z");
  stroke: none;
}

</style>
