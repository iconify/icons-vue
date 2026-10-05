<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="npmdckiuw"/><path class="ygeb0bb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-pen-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.npmdckiuw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 22H2C1.44772 22 1 21.5523 1 21V20C1 16.134 4.13402 13 8 13H10V22ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

.ygeb0bb4a {
  d: path("M21.5607 14.5607L16.5355 19.5858L13 21L14.4142 17.4645L19.4393 12.4393C19.7207 12.158 20.1022 12 20.5 12C20.8978 12 21.2794 12.158 21.5607 12.4393C21.842 12.7206 22 13.1022 22 13.5C22 13.8978 21.842 14.2793 21.5607 14.5607Z");
}

</style>
