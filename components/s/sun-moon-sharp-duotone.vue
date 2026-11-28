<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p8xpngxdv"/><path class="ipq6als4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-moon-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ipq6als4t {
  d: path("M13 5.5L13 1M16.8891 7.1109L20.0711 3.9289M18.5 11L23 11");
}

.p8xpngxdv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.3431 9.3431C1.8965 10.7898 1 12.7911 1 15C1 19.4183 4.5817 23 9 23C13.4183 23 17 19.4183 17 15C17 14.4477 16.5523 14 16 14C15.7836 14 15.5731 14.0702 15.4 14.2C14.7076 14.7193 13.8655 15 13 15C10.7909 15 9 13.2091 9 11C9 10.1345 9.2807 9.2924 9.8 8.6C9.9298 8.4269 10 8.2164 10 8C10 7.4477 9.5523 7 9 7C6.7911 7 4.7898 7.8965 3.3431 9.3431Z");
  stroke: none;
}

</style>
