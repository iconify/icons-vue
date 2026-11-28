<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o0ubd-spe"/><path class="vtb1sfk9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-braces-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0ubd-spe {
  d: path("M3 3H21V21H3V3Z");
}

.vtb1sfk9d {
  d: path("M11 7H9V11L8 12L9 13V17H11M13 7H15V11L16 12L15 13V17H13");
}

</style>
