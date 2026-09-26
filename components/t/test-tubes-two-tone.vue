<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z23h2kbhj"/><path class="oqeq4_wjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqeq4_wjs {
  d: path("M4 2L8 2C8.5523 2 9 2.4477 9 3L9 19C9 20.6569 7.6569 22 6 22C4.3431 22 3 20.6569 3 19L3 3C3 2.4477 3.4477 2 4 2ZM2 2L10 2M3 13L9 13M16 2L20 2C20.5523 2 21 2.4477 21 3L21 19C21 20.6569 19.6569 22 18 22C16.3431 22 15 20.6569 15 19L15 3C15 2.4477 15.4477 2 16 2ZM14 2L22 2M15 16L21 16");
}

.z23h2kbhj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L8 1C9.1046 1 10 1.8954 10 3L10 19C10 21.2091 8.2091 23 6 23C3.7909 23 2 21.2091 2 19L2 3C2 1.8954 2.8954 1 4 1ZM16 1L20 1C21.1046 1 22 1.8954 22 3L22 19C22 21.2091 20.2091 23 18 23C15.7909 23 14 21.2091 14 19L14 3C14 1.8954 14.8954 1 16 1Z");
  stroke: none;
}

</style>
