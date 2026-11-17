<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f-mvfrsrl"/><path class="fxp4x3_ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sink-two-tone" /></template>
<style>
.f-mvfrsrl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 19C21 21.209 19.2092 23 17 23H7C4.7908 23 3 21.209 3 19V13H21V19Z");
  stroke: none;
}

.fxp4x3_ym {
  d: path("M2 14H22M4 14V19C4 20.657 5.3431 22 7 22H17C18.6569 22 20 20.657 20 19V14M12 14V5C12 3.343 13.3431 2 15 2C16.6569 2 18 3.343 18 5V6M16 14V11C16 10.448 16.4477 10 17 10H20M8 14V11C8 10.448 7.5523 10 7 10H4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
