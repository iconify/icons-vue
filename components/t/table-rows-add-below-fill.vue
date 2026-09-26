<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a0ltxiykj"/><path class="bjrfcyy_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-add-below-fill" /></template>
<style>
.a0ltxiykj {
  fill: currentColor;
  d: path("M3 11L21 11L21 5C21 3.3431 19.6569 2 18 2L6 2C4.3431 2 3 3.3431 3 5L3 11Z");
  stroke: none;
}

.bjrfcyy_s {
  d: path("M5 19.8284C3.8014 19.4046 3 18.2713 3 17L3 5C3 3.3431 4.3431 2 6 2L18 2C19.6569 2 21 3.3431 21 5L21 17C21 18.2713 20.1986 19.4046 19 19.8284M3 11L21 11M12 16L12 22M9 19L15 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
