<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="htsq3ccqb"/><path class="ygeb0bb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-pen-duotone" /></template>
<style>
.htsq3ccqb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 12C9.55228 12 10 12.4477 10 13V21C10 21.5523 9.55228 22 9 22H3C1.89542 22 1 21.1046 1 20V19C1 15.134 4.13402 12 8 12H9ZM9 2C11.2092 2 13 3.79082 13 6C13 8.20918 11.2092 10 9 10C6.79094 10 5 8.20921 5 6C5 3.79079 6.79094 2 9 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ygeb0bb4a {
  d: path("M21.5607 14.5607L16.5355 19.5858L13 21L14.4142 17.4645L19.4393 12.4393C19.7207 12.158 20.1022 12 20.5 12C20.8978 12 21.2794 12.158 21.5607 12.4393C21.842 12.7206 22 13.1022 22 13.5C22 13.8978 21.842 14.2793 21.5607 14.5607Z");
}

</style>
