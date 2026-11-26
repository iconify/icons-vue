<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="prkyegonc"/><path class="pgb99obzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-move-after-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pgb99obzj {
  d: path("M19.8284 5C19.4046 3.8014 18.2713 3 17 3L5 3C3.3431 3 2 4.3431 2 6L2 18C2 19.6569 3.3431 21 5 21L17 21C18.2713 21 19.4046 20.1986 19.8284 19M11 3L11 21M16 12H22M19 9L22 12L19 15");
}

.prkyegonc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3L5 3C3.3431 3 2 4.3431 2 6L2 18C2 19.6569 3.3431 21 5 21L11 21Z");
  stroke: none;
}

</style>
