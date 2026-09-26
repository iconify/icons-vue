<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gqb9m7h-f"/><path class="wfvx-jtqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-previous-two-tone" /></template>
<style>
.gqb9m7h-f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 3.7909 3.7909 2 6 2L18 2C20.2091 2 22 3.7909 22 6ZM17 3L17 21L18 21C19.6569 21 21 19.6569 21 18L21 6C21 4.3431 19.6569 3 18 3L17 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wfvx-jtqi {
  d: path("M21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 4.3431 4.3431 3 6 3L18 3C19.6569 3 21 4.3431 21 6ZM17 3L17 21M8 3L8 5M8 21L8 19M13 12L7 12M10 9L7 12L10 15");
}

</style>
