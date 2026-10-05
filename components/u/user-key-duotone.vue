<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mej7b4bsh"/><path class="t9dbu48so"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-key-duotone" /></template>
<style>
.mej7b4bsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 13C10.5523 13 11 13.4477 11 14V21C11 21.5523 10.5523 22 10 22H3C1.89542 22 1 21.1046 1 20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t9dbu48so {
  d: path("M18 19C18 20.1046 17.1046 21 16 21C14.8954 21 14 20.1046 14 19C14 17.8954 14.8954 17 16 17C17.1046 17 18 17.8954 18 19ZM17.4142 17.5858L21.5 13.5M20.4393 14.5607L22 16.1214");
}

</style>
