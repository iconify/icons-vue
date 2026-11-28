<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o0ubd-spe"/><path class="bop0gfbew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-search-sharp" /></template>
<style>
.bop0gfbew {
  d: path("M13.39 13.3905L16.535 16.5355M14.357 11.0572C14.357 12.8796 12.88 14.357 11.057 14.357C9.235 14.357 7.757 12.8796 7.757 11.0572C7.757 9.2347 9.235 7.7574 11.057 7.7574C12.88 7.7574 14.357 9.2347 14.357 11.0572Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0ubd-spe {
  d: path("M3 3H21V21H3V3Z");
}

</style>
