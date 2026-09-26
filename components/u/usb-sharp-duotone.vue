<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k3drzc9fl"/><path class="ylejacb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k3drzc9fl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 12C7 13.6569 5.6569 15 4 15C2.3431 15 1 13.6569 1 12C1 10.3431 2.3431 9 4 9C5.6569 9 7 10.3431 7 12ZM17.5 6C17.5 7.6569 16.1569 9 14.5 9C12.8431 9 11.5 7.6569 11.5 6C11.5 4.3431 12.8431 3 14.5 3C16.1569 3 17.5 4.3431 17.5 6ZM11 15L15 15C15.5523 15 16 15.4477 16 16L16 20C16 20.5523 15.5523 21 15 21L11 21C10.4477 21 10 20.5523 10 20L10 16C10 15.4477 10.4477 15 11 15Z");
  stroke: none;
}

.ylejacb2h {
  d: path("M6 12L22 12M10 12L13.3 7.6M10 12L13 16M19.7071 9.7071L22 12L19.7071 14.2929");
}

</style>
