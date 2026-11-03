<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hxrpt8qkm"/><path class="i6shepb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:outdoor-seating-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hxrpt8qkm {
  fill: currentColor;
  d: path("M2.1758 9L2 9C1.4477 9 1 8.5523 1 8C1 7.7661 1.082 7.5395 1.2318 7.3598L1.3443 7.2248L3.0309 5.2009C5.2491 2.5391 8.535 1 12 1C15.465 1 18.7509 2.5391 20.9691 5.2009L22.6557 7.2248L22.7682 7.3598C22.918 7.5395 23 7.7661 23 8C23 8.5523 22.5523 9 22 9L2.1758 9Z");
  stroke: none;
}

.i6shepb6c {
  stroke-opacity: 0.4;
  d: path("M12 8L12 23M6 14L18 14M22 11L22 23M22 18L17 18L17 23M2 11L2 23M2 18L7 18L7 23");
}

</style>
