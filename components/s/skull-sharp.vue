<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bf264u6pg"/><path clip-rule="evenodd" class="wdmb74bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skull-sharp" /></template>
<style>
.bf264u6pg {
  d: path("M6 17.7082C4.0911 16.0008 3 13.5611 3 11C3 6.0294 7.0294 2 12 2C16.9706 2 21 6.0294 21 11C21 13.5611 19.9089 16.0008 18 17.7082L18 22L6 22ZM10 22L10 19M14 22L14 19M10.4562 16.47L12 14L13.5438 16.47");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wdmb74bkm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 11C10 11.8284 9.3284 12.5 8.5 12.5C7.6716 12.5 7 11.8284 7 11C7 10.1716 7.6716 9.5 8.5 9.5C9.3284 9.5 10 10.1716 10 11ZM17 11C17 11.8284 16.3284 12.5 15.5 12.5C14.6716 12.5 14 11.8284 14 11C14 10.1716 14.6716 9.5 15.5 9.5C16.3284 9.5 17 10.1716 17 11Z");
  stroke: none;
}

</style>
