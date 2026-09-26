<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tazu73b4s"/><path class="p_bzldb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_bzldb-i {
  d: path("M19 11C19 15.4184 15.4184 19 11 19C6.5816 19 3 15.4184 3 11C3 6.5816 6.5816 3 11 3C15.4184 3 19 6.5816 19 11ZM17 17L21 21");
}

.tazu73b4s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2C15.9706 2 20 6.0294 20 11C20 15.9706 15.9706 20 11 20C6.0294 20 2 15.9706 2 11C2 6.0294 6.0294 2 11 2Z");
  stroke: none;
}

</style>
