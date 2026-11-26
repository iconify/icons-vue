<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="njchc7bcm"/><path class="osiju45cn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-distort-fill" /></template>
<style>
.njchc7bcm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2L6 2C7.1046 2 8 2.8954 8 4L8 6C8 7.1046 7.1046 8 6 8L4 8C2.8954 8 2 7.1046 2 6L2 4C2 2.8954 2.8954 2 4 2ZM19 5L20 5C21.1046 5 22 5.8954 22 7L22 9C22 10.1046 21.1046 11 20 11L18 11C16.8954 11 16 10.1046 16 9L16 7C16 5.8954 16.8954 5 18 5ZM17 16L18 16C19.1046 16 20 16.8954 20 18L20 20C20 21.1046 19.1046 22 18 22L16 22C14.8954 22 14 21.1046 14 20L14 18C14 16.8954 14.8954 16 16 16ZM7 12L8 12C9.1046 12 10 12.8954 10 14L10 16C10 17.1046 9.1046 18 8 18L6 18C4.8954 18 4 17.1046 4 16L4 14C4 12.8954 4.8954 12 6 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osiju45cn {
  d: path("M7 5L17 8M19 10L17 17M15 19L9 15M7 13L5 7");
}

</style>
