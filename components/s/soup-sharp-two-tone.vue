<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="th7qmabfh"/><path class="vaa1bn60q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:soup-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.th7qmabfh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11L22 11C22.5523 11 23 11.4477 23 12C23 12.0738 22.9918 12.1475 22.9756 12.2195C21.8206 17.3529 17.2617 21 12 21C6.7383 21 2.1794 17.3529 1.0244 12.2195C1.0082 12.1475 1 12.0738 1 12C1 11.4477 1.4477 11 2 11Z");
  stroke: none;
}

.vaa1bn60q {
  d: path("M2 12L22 12C20.9477 16.6771 16.794 20 12 20C7.206 20 3.0523 16.6771 2 12ZM4 20L20 20M5 9L5 8C5 7.2131 5.3705 6.4721 6 6C6.6295 5.5279 7 4.7869 7 4L7 3M11 9L11 8C11 7.2131 11.3705 6.4721 12 6C12.6295 5.5279 13 4.7869 13 4L13 3M17 9L17 8C17 7.2131 17.3705 6.4721 18 6C18.6295 5.5279 19 4.7869 19 4L19 3");
}

</style>
