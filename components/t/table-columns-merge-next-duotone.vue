<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cp4rs98vb"/><path class="meznc0b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-next-duotone" /></template>
<style>
.cp4rs98vb {
  stroke-opacity: 0.4;
  d: path("M3 6L3 18C3 19.6569 4.3431 21 6 21L18 21C19.6569 21 21 19.6569 21 18L21 6C21 4.3431 19.6569 3 18 3L6 3C4.3431 3 3 4.3431 3 6ZM7 3L7 21M16 3L16 5M16 21L16 19");
}

.meznc0b-s {
  d: path("M11 12L17 12M14 9L17 12L14 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
