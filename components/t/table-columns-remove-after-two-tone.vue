<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="naqffhgja"/><path class="m1-yh02qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-remove-after-two-tone" /></template>
<style>
.m1-yh02qu {
  d: path("M19.8284 5C19.4046 3.8014 18.2713 3 17 3L5 3C3.3431 3 2 4.3431 2 6L2 18C2 19.6569 3.3431 21 5 21L17 21C18.2713 21 19.4046 20.1986 19.8284 19M11 3L11 21M16 9L22 15M22 9L16 15");
}

.naqffhgja {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3L11 21L5 21C3.3431 21 2 19.6569 2 18L2 6C2 4.3431 3.3431 3 5 3L11 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
