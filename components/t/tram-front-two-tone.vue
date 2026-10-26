<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wd9rvzmxg"/><path class="t64miynmb"/><path clip-rule="evenodd" class="v8bb7zbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t64miynmb {
  d: path("M7 6L17 6C18.6569 6 20 7.3431 20 9L20 17C20 18.6569 18.6569 20 17 20L7 20C5.3431 20 4 18.6569 4 17L4 9C4 7.3431 5.3431 6 7 6ZM4 12L20 12M8 2L16 2M10 6L12 2L14 6M8 20L7 22M16 20L17 22");
}

.v8bb7zbok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16ZM17 16C17 16.5523 16.5523 17 16 17C15.4477 17 15 16.5523 15 16C15 15.4477 15.4477 15 16 15C16.5523 15 17 15.4477 17 16Z");
  stroke: none;
}

.wd9rvzmxg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 5L17 5C19.2092 5 21 6.7908 21 9L21 17C21 19.2092 19.2092 21 17 21L7 21C4.7908 21 3 19.2092 3 17L3 9C3 6.7908 4.7908 5 7 5Z");
  stroke: none;
}

</style>
