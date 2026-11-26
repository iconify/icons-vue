<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b-es3slda"/><path class="itepumbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snorkel-duotone" /></template>
<style>
.b-es3slda {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 7L15 7C17.2092 7 19 8.7908 19 11C19 13.7614 16.7614 16 14 16L12.9142 16C12.3837 16 11.875 15.7892 11.5 15.4142L10 13.9L8.5 15.4142C8.125 15.7892 7.6163 16 7.0858 16L6 16C3.2386 16 1 13.7614 1 11C1 8.7908 2.7908 7 5 7Z");
  stroke: none;
}

.itepumbtr {
  d: path("M22 5L22 14C22 16.7614 19.7614 19 17 19L10 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
