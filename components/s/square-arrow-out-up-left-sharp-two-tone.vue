<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i9y1osboo"/><path class="pszj34une"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-up-left-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i9y1osboo {
  stroke-opacity: 0.4;
  d: path("M14 7L21 7L21 21L7 21L7 14");
}

.pszj34une {
  d: path("M11.2929 11.2929L3.1464 3.1464M12 3L3 3L3 12");
}

</style>
