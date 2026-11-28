<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0okwq2sh"/><path class="iqwmeh4gd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-globe-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iqwmeh4gd {
  d: path("M4 12L20 12M12 2C14.6667 5 16 8.5 16 12C16 15.5 14.6667 19 12 22C9.3333 19 8 15.5 8 12C8 8.5 9.3333 5 12 2Z");
}

.v0okwq2sh {
  stroke-opacity: 0.4;
  d: path("M20 5.3088L20 15.778L18.612 17.5729C17.4097 19.1277 15.5033 20.8703 12.8298 21.8525C12.2945 22.0492 11.7055 22.0492 11.1702 21.8525C8.4967 20.8703 6.5903 19.1277 5.388 17.5729L4 15.7778L4 5.3088L5.1825 5.1684C7.8303 4.8543 9.8295 3.5322 11.0242 2.3731C11.537 1.8756 12.463 1.8756 12.9758 2.3731C14.1705 3.5322 16.1697 4.8543 18.8175 5.1684L20 5.3088Z");
}

</style>
