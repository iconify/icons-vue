<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="um-32tbyu"/><path class="c2gzpd_8m"/><path clip-rule="evenodd" class="dq_vav-xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pill-bottle-sharp-two-tone" /></template>
<style>
.c2gzpd_8m {
  d: path("M5 7V22H19V7M4 2H20V7H4V2Z");
}

.dq_vav-xs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 10.5H13C13.276 10.5 13.5 10.72 13.5 11V12.5C13.5 12.78 13.724 13 14 13H15.5C15.776 13 16 13.22 16 13.5V15.5C16 15.78 15.776 16 15.5 16H14C13.724 16 13.5 16.22 13.5 16.5V18C13.5 18.28 13.276 18.5 13 18.5H11C10.724 18.5 10.5 18.28 10.5 18V16.5C10.5 16.22 10.276 16 10 16H8.5C8.224 16 8 15.78 8 15.5V13.5C8 13.22 8.224 13 8.5 13H10C10.276 13 10.5 12.78 10.5 12.5V11C10.5 10.72 10.724 10.5 11 10.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.um-32tbyu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 1C20.552 1 21 1.45 21 2V7C21 7.55 20.552 8 20 8V22C20 22.55 19.552 23 19 23H5C4.448 23 4 22.55 4 22V8C3.448 8 3 7.55 3 7V2C3 1.45 3.448 1 4 1H20Z");
  stroke: none;
}

</style>
