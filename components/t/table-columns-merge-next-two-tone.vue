<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ss4mudbps"/><path class="an7o96bab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-next-two-tone" /></template>
<style>
.an7o96bab {
  d: path("M3 6L3 18C3 19.6569 4.3431 21 6 21L18 21C19.6569 21 21 19.6569 21 18L21 6C21 4.3431 19.6569 3 18 3L6 3C4.3431 3 3 4.3431 3 6ZM7 3L7 21M16 3L16 5M16 21L16 19M11 12L17 12M14 9L17 12L14 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ss4mudbps {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6L2 18C2 20.2091 3.7909 22 6 22L18 22C20.2091 22 22 20.2091 22 18L22 6C22 3.7909 20.2091 2 18 2L6 2C3.7909 2 2 3.7909 2 6ZM7 3L7 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 4.3431 4.3431 3 6 3L7 3Z");
  stroke: none;
}

</style>
