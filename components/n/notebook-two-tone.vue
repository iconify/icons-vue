<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="km88rpbno"/><path class="fdj7tvbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-two-tone" /></template>
<style>
.fdj7tvbjr {
  d: path("M5 5C5 3.3431 6.3431 2 8 2L18 2C19.6569 2 21 3.3431 21 5L21 19C21 20.6569 19.6569 22 18 22L8 22C6.3431 22 5 20.6569 5 19L5 5ZM3 7L7 7M3 12L7 12M3 17L7 17M17 6L17 18");
}

.km88rpbno {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5C4 2.7909 5.7909 1 8 1L18 1C20.2091 1 22 2.7909 22 5L22 19C22 21.2091 20.2091 23 18 23L8 23C5.7909 23 4 21.2091 4 19L4 5Z");
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
