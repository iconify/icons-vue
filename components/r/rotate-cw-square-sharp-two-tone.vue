<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ohktr909v"/><path class="hhjv-fbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-cw-square-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hhjv-fbbe {
  d: path("M9.312 1.73L12 4.25L9.284 6.8M12 4.25H4V10M9 22V11H20V22H9Z");
}

.ohktr909v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10C20.552 10 21 10.45 21 11V22C21 22.55 20.552 23 20 23H9C8.448 23 8 22.55 8 22V11C8 10.45 8.448 10 9 10H20ZM12.684 3.52C12.885 3.71 13 3.97 13 4.25C13 4.53 12.885 4.79 12.684 4.98L9.968 7.53L8.6 6.07L9.471 5.25H5V10H3V4.25C3 3.7 3.448 3.25 4 3.25H9.472L8.628 2.46L9.995 1L12.684 3.52Z");
  stroke: none;
}

</style>
