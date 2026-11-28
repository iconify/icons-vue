<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="woeb2-brx"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.woeb2-brx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 18L18 21C18 21.5523 17.5523 22 17 22L3 22C2.4477 22 2 21.5523 2 21L2 17C2 16.4477 2.4477 16 3 16L4 16C5.1046 16 6 15.1046 6 14C6 12.8954 5.1046 12 4 12L3 12C2.4477 12 2 11.5523 2 11L2 7C2 6.4477 2.4477 6 3 6L6 6ZM7.0052 3.3483C7.738 2.5213 8.8081 2 10 2C12.2092 2 14 3.7908 14 6L17 6C17.5523 6 18 6.4477 18 7L18 10C20.2092 10 22 11.7908 22 14C22 15.1919 21.4787 16.262 20.6517 16.9948Z");
  stroke: none;
}

</style>
