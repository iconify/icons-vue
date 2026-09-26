<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m5elujb-l"/><path class="wfvx-jtqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-previous-fill" /></template>
<style>
.m5elujb-l {
  fill: currentColor;
  d: path("M17 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L17 21L17 3Z");
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
