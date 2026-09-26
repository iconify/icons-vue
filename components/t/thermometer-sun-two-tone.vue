<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dj05c4b-z"/><path class="h9-w-wbzx"/><path class="xcyk673ka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sun-two-tone" /></template>
<style>
.dj05c4b-z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5 5C13.5 2.7909 15.2909 1 17.5 1C19.7091 1 21.5 2.7909 21.5 5L21.5 13.7251C22.4634 14.7459 23 16.0964 23 17.5C23 20.5376 20.5376 23 17.5 23C14.4624 23 12 20.5376 12 17.5C12 16.0964 12.5366 14.7459 13.5 13.7251L13.5 5Z");
  stroke: none;
}

.h9-w-wbzx {
  d: path("M14.5 5C14.5 3.3431 15.8431 2 17.5 2C19.1569 2 20.5 3.3431 20.5 5L20.5 13.7251C20.5 13.9803 20.5976 14.2258 20.7727 14.4114C21.5609 15.2466 22 16.3516 22 17.5C22 19.9853 19.9853 22 17.5 22C15.0147 22 13 19.9853 13 17.5C13 16.3516 13.4391 15.2466 14.2273 14.4114C14.4024 14.2258 14.5 13.9803 14.5 13.7251L14.5 5ZM10.5 12.4495C10.3355 12.4831 10.1679 12.5 10 12.5C8.6193 12.5 7.5 11.3807 7.5 10C7.5 8.6193 8.6193 7.5 10 7.5C10.1679 7.5 10.3355 7.5169 10.5 7.5505M5.4038 14.5962L4.3431 15.6569M3.5 10L2 10M5.4038 5.4038L4.3431 4.3431M10 3.5L10 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xcyk673ka {
  fill: currentColor;
  d: path("M19 17.5C19 18.3284 18.3284 19 17.5 19C16.6716 19 16 18.3284 16 17.5C16 16.6716 16.6716 16 17.5 16C18.3284 16 19 16.6716 19 17.5Z");
  stroke: none;
}

</style>
