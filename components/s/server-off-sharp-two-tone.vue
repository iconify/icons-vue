<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c2brgfdnt"/><path clip-rule="evenodd" class="g5h5rcqdm"/><path class="y06uacbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-off-sharp-two-tone" /></template>
<style>
.c2brgfdnt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 11H4C3.448 11 3 10.552 3 10V3L11 11ZM21 21V22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V14C3 13.448 3.448 13 4 13H13L21 21ZM4.743 1H20C20.552 1 21 1.448 21 2V10C21 10.552 20.552 11 20 11H14.743L4.743 1ZM16.743 13H20C20.552 13 21 13.448 21 14V17.257L16.743 13Z");
  stroke: none;
}

.g5h5rcqdm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 18C9 18.552 8.552 19 8 19C7.448 19 7 18.552 7 18C7 17.448 7.448 17 8 17C8.552 17 9 17.448 9 18ZM13 18C13 18.552 12.552 19 12 19C11.448 19 11 18.552 11 18C11 17.448 11.448 17 12 17C12.552 17 13 17.448 13 18Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y06uacbov {
  d: path("M10 10H4V4M20 20V22H4V14H14M1.707 1.707L22.293 22.293");
}

</style>
