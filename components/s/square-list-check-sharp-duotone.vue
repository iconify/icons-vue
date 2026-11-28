<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k74zdac1b"/><path class="r0cwtho5s"/><path clip-rule="evenodd" class="prbod8bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-check-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k74zdac1b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2H21C21.552 2 22 2.448 22 3V11C22 11.552 21.552 12 21 12H12V21C12 21.552 11.552 22 11 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2Z");
  stroke: none;
}

.prbod8bku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 8C9 8.552 8.552 9 8 9C7.448 9 7 8.552 7 8C7 7.448 7.448 7 8 7C8.552 7 9 7.448 9 8ZM9 12C9 12.552 8.552 13 8 13C7.448 13 7 12.552 7 12C7 11.448 7.448 11 8 11C8.552 11 9 11.448 9 12ZM9 16C9 16.552 8.552 17 8 17C7.448 17 7 16.552 7 16C7 15.448 7.448 15 8 15C8.552 15 9 15.448 9 16Z");
  stroke: none;
}

.r0cwtho5s {
  d: path("M11 8H17M14.707 17.707L17 20L21.293 15.707");
}

</style>
