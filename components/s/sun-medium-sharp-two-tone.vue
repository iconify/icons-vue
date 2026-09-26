<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gv2jrdtmw"/><path class="xoy3_wr4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-medium-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gv2jrdtmw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.5 12C17.5 15.0376 15.0376 17.5 12 17.5C8.9624 17.5 6.5 15.0376 6.5 12C6.5 8.9624 8.9624 6.5 12 6.5C15.0376 6.5 17.5 8.9624 17.5 12Z");
  stroke: none;
}

.xoy3_wr4r {
  d: path("M16.5 12C16.5 14.4853 14.4853 16.5 12 16.5C9.5147 16.5 7.5 14.4853 7.5 12C7.5 9.5147 9.5147 7.5 12 7.5C14.4853 7.5 16.5 9.5147 16.5 12ZM19.5 12L22 12M17.3033 17.3033L19.0711 19.0711M12 19.5L12 22M6.6967 17.3033L4.9289 19.0711M4.5 12L2 12M6.6967 6.6967L4.9289 4.9289M12 4.5L12 2M17.3033 6.6967L19.0711 4.9289");
}

</style>
