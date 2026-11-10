<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s0fnrzb7x"/><path class="gf6b5nkeq"/><path clip-rule="evenodd" class="iwenprebt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pill-bottle-two-tone" /></template>
<style>
.gf6b5nkeq {
  d: path("M5 7V19C5 20.66 6.3431 22 8 22H16C17.6569 22 19 20.66 19 19V7M5.5 2H18.5C19.3284 2 20 2.67 20 3.5V5.5C20 6.33 19.3284 7 18.5 7H5.5C4.6716 7 4 6.33 4 5.5V3.5C4 2.67 4.6716 2 5.5 2Z");
}

.iwenprebt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 10.5H13C13.2761 10.5 13.5 10.72 13.5 11V12.5C13.5 12.78 13.7239 13 14 13H15.5C15.7761 13 16 13.22 16 13.5V15.5C16 15.78 15.7761 16 15.5 16H14C13.7239 16 13.5 16.22 13.5 16.5V18C13.5 18.28 13.2761 18.5 13 18.5H11C10.7239 18.5 10.5 18.28 10.5 18V16.5C10.5 16.22 10.2761 16 10 16H8.5C8.2239 16 8 15.78 8 15.5V13.5C8 13.22 8.2239 13 8.5 13H10C10.2761 13 10.5 12.78 10.5 12.5V11C10.5 10.72 10.7239 10.5 11 10.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s0fnrzb7x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.5 1C19.8807 1 21 2.12 21 3.5V5.5C21 6.32 20.6061 7.04 20 7.5V19C20 21.21 18.2092 23 16 23H8C5.7908 23 4 21.21 4 19V7.5C3.3939 7.04 3 6.32 3 5.5V3.5C3 2.12 4.1193 1 5.5 1H18.5Z");
  stroke: none;
}

</style>
