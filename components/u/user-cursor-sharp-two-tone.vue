<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bto-1lbtl"/><path class="ycrtapbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-cursor-sharp-two-tone" /></template>
<style>
.bto-1lbtl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.8293 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H10.8293V22ZM9 2C11.2092 2 13 3.7908 13 6C13 8.2092 11.2092 10 9 10C6.7909 10 5 8.2092 5 6C5 3.7908 6.7909 2 9 2ZM18.2504 13.3369L22.3358 14.7933C22.7341 14.9352 23 15.3124 23 15.7352C23 16.1185 22.7809 16.4681 22.4358 16.6352L19.2713 18.1677L17.4856 21.4751C17.3111 21.7984 16.9732 22 16.6057 22C16.1773 22 15.7965 21.7271 15.6588 21.3215L12.8823 13.144C12.8471 13.0405 12.8292 12.9318 12.8292 12.8225C12.8292 12.2702 13.2769 11.8225 13.8292 11.8225C13.9436 11.8225 14.0572 11.8421 14.165 11.8806Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ycrtapbxe {
  d: path("M9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3432 9 6 7.6569 6 6C6 4.3431 7.3432 3 9 3ZM10.8293 21L2 21L2 19C2 15.6863 4.6863 13 8 13L10.8293 13M16.6057 21L13.8292 12.8225L22 15.7352L18.5448 17.4084L16.6057 21Z");
}

</style>
