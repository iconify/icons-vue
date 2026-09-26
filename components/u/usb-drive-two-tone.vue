<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ynywh-e5i"/><path class="md58pobxu"/><path class="zna1w6bmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-drive-two-tone" /></template>
<style>
.md58pobxu {
  d: path("M4 4L12 4C13.1046 4 14 4.8954 14 6L14 18C14 19.1046 13.1046 20 12 20L4 20C2.8954 20 2 19.1046 2 18L2 6C2 4.8954 2.8954 4 4 4ZM14 6L20 6C21.1046 6 22 6.8954 22 8L22 16C22 17.1046 21.1046 18 20 18L14 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ynywh-e5i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L12 3C13.2713 3 14.4046 3.8014 14.8284 5L20 5C21.6569 5 23 6.3431 23 8L23 16C23 17.6569 21.6569 19 20 19L14.8284 19C14.4046 20.1986 13.2713 21 12 21L4 21C2.3431 21 1 19.6569 1 18L1 6C1 4.3431 2.3431 3 4 3Z");
  stroke: none;
}

.zna1w6bmi {
  fill: currentColor;
  d: path("M19 10C19 10.5523 18.5523 11 18 11C17.4477 11 17 10.5523 17 10C17 9.4477 17.4477 9 18 9C18.5523 9 19 9.4477 19 10ZM19 14C19 14.5523 18.5523 15 18 15C17.4477 15 17 14.5523 17 14C17 13.4477 17.4477 13 18 13C18.5523 13 19 13.4477 19 14Z");
  stroke: none;
}

</style>
