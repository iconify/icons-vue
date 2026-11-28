<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ugse86bkf"/><path class="ypd2_6smq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-z-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ugse86bkf {
  fill: currentColor;
  d: path("M3.9289 20.0711C2.1204 18.2625 1 15.7612 1 13C1 7.4771 5.4771 3 11 3C11.5523 3 12 3.4477 12 4C12 4.2271 11.9227 4.4474 11.7809 4.6247C10.061 6.7745 10.2326 9.8738 12.1794 11.8206C14.1262 13.7674 17.2255 13.939 19.3753 12.2191C19.5526 12.0773 19.7729 12 20 12C20.5523 12 21 12.4477 21 13C21 18.5229 16.5229 23 11 23C8.2388 23 5.7375 21.8796 3.9289 20.0711Z");
  stroke: none;
}

.ypd2_6smq {
  d: path("M15 2L22 2L16 8L23 8");
}

</style>
