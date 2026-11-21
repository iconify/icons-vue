<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q_juv0bfw"/><path class="po2s8q89o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-z-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.po2s8q89o {
  d: path("M20 13C20 17.9706 15.9706 22 11 22C6.0294 22 2 17.9706 2 13C2 8.0294 6.0294 4 11 4C8.9618 6.5477 9.1652 10.2206 11.4723 12.5277C13.7794 14.8348 17.4523 15.0382 20 13ZM22 9H17.1466C16.71 9 16.4831 8.4797 16.7802 8.15977L21.7198 2.84023C22.0169 2.5203 21.79 2 21.3534 2H16.5");
}

.q_juv0bfw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.9289 20.0711C2.1204 18.2625 1 15.7612 1 13C1 7.4771 5.4771 3 11 3C11.5523 3 12 3.4477 12 4C12 4.2271 11.9227 4.4474 11.7809 4.6247C10.061 6.7745 10.2326 9.8738 12.1794 11.8206C14.1262 13.7674 17.2255 13.939 19.3753 12.2191C19.5526 12.0773 19.7729 12 20 12C20.5523 12 21 12.4477 21 13C21 18.5229 16.5229 23 11 23C8.2388 23 5.7375 21.8796 3.9289 20.0711Z");
  stroke: none;
}

</style>
