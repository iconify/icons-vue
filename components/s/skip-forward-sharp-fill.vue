<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j1-j4unxp"/><path class="afoagpens"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skip-forward-sharp-fill" /></template>
<style>
.afoagpens {
  d: path("M19 4L19 20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j1-j4unxp {
  fill: currentColor;
  d: path("M5.5551 4.1682L16.0443 11.1682C16.6375 11.5641 16.6375 12.4359 16.0443 12.8318L5.5551 19.8318C4.8906 20.2753 4 19.7989 4 19L4 5C4 4.2011 4.8906 3.7247 5.5551 4.1682Z");
  stroke: none;
}

</style>
