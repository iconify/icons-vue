<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xhkyucb5p"/><path class="insp6uw0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-ringing-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.insp6uw0p {
  d: path("M7 4L17 4L17 20L7 20ZM10 8L11 8L13 8L14 8M21.0175 7.5633L21.3675 8.5C21.7858 9.6195 22 10.8049 22 12C22 13.1951 21.7858 14.3805 21.3675 15.5L21.0175 16.4367M2.9825 16.4367L2.6325 15.5C2.2142 14.3805 2 13.1951 2 12C2 10.8049 2.2142 9.6195 2.6325 8.5L2.9825 7.5633");
}

.xhkyucb5p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 3C17.5523 3 18 3.44772 18 4V20C18 20.5523 17.5523 21 17 21H7C6.44772 21 6 20.5523 6 20V4C6 3.44772 6.44772 3 7 3H17Z");
  stroke: none;
}

</style>
