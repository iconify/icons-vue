<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q_juv0bfw"/><path class="mekxy4b_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-z-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mekxy4b_l {
  d: path("M20 13C20 17.9706 15.9706 22 11 22C6.0294 22 2 17.9706 2 13C2 8.0294 6.0294 4 11 4C8.9618 6.5477 9.1652 10.2206 11.4723 12.5277C13.7794 14.8348 17.4523 15.0382 20 13ZM15 2L22 2L16 8L23 8");
}

.q_juv0bfw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.9289 20.0711C2.1204 18.2625 1 15.7612 1 13C1 7.4771 5.4771 3 11 3C11.5523 3 12 3.4477 12 4C12 4.2271 11.9227 4.4474 11.7809 4.6247C10.061 6.7745 10.2326 9.8738 12.1794 11.8206C14.1262 13.7674 17.2255 13.939 19.3753 12.2191C19.5526 12.0773 19.7729 12 20 12C20.5523 12 21 12.4477 21 13C21 18.5229 16.5229 23 11 23C8.2388 23 5.7375 21.8796 3.9289 20.0711Z");
  stroke: none;
}

</style>
