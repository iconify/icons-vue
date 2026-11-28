<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jg1qo7ohz"/><path class="vmx6_o-fu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:users-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jg1qo7ohz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 12L10 12C13.7279 12 17 15.2721 17 19L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 19C1 15.2721 4.2721 12 8 12ZM9 2C11.0711 2 13 3.9289 13 6C13 8.0711 11.0711 10 9 10C6.9289 10 5 8.0711 5 6C5 3.9289 6.9289 2 9 2Z");
  stroke: none;
}

.vmx6_o-fu {
  d: path("M15 3L16 3C17.6569 3 19 4.3431 19 6C19 7.6569 17.6569 9 16 9L15 9M17.4121 13.0823L18.3333 13.4713C20.554 14.409 22 16.589 22 19V20C22 20.5523 21.5523 21 21 21L20 21");
}

</style>
