<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w23_kmrec"/><path class="p4pqz_bvw"/><path class="zna1w6bmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-drive-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4pqz_bvw {
  d: path("M14 6L20 6C21.1046 6 22 6.8954 22 8L22 16C22 17.1046 21.1046 18 20 18L14 18");
}

.w23_kmrec {
  fill: currentColor;
  d: path("M4 3L12 3C13.6569 3 15 4.3431 15 6L15 18C15 19.6569 13.6569 21 12 21L4 21C2.3431 21 1 19.6569 1 18L1 6C1 4.3431 2.3431 3 4 3Z");
  stroke: none;
}

.zna1w6bmi {
  fill: currentColor;
  d: path("M19 10C19 10.5523 18.5523 11 18 11C17.4477 11 17 10.5523 17 10C17 9.4477 17.4477 9 18 9C18.5523 9 19 9.4477 19 10ZM19 14C19 14.5523 18.5523 15 18 15C17.4477 15 17 14.5523 17 14C17 13.4477 17.4477 13 18 13C18.5523 13 19 13.4477 19 14Z");
  stroke: none;
}

</style>
