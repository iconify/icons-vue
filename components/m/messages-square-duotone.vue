<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9ujp84gn"/><path class="vpx0usb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square-duotone" /></template>
<style>
.j9ujp84gn {
  fill: currentColor;
  d: path("M14 9L19 9C20.6569 9 22 10.3431 22 12L22 21C22 21.5523 21.5523 22 21 22C20.7348 22 20.4804 21.8946 20.2929 21.7071L17.5858 19L14 19C12.3431 19 11 17.6569 11 16L11 12C11 10.3431 12.3431 9 14 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vpx0usb4d {
  stroke-opacity: 0.4;
  d: path("M6 13L3 16L3 5C3 3.8954 3.8954 3 5 3L14 3C15.1046 3 16 3.8954 16 5L16 6");
}

</style>
