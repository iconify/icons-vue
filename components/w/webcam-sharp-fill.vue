<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="t7xt-xi-a"/><path class="n511-ub4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:webcam-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n511-ub4l {
  d: path("M12 18L12 22M5 22L19 22");
}

.t7xt-xi-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 18C21 18.5523 20.5523 19 20 19L4 19C3.4477 19 3 18.5523 3 18L3 2C3 1.4477 3.4477 1 4 1ZM16 10C16 7.7909 14.2091 6 12 6C9.7909 6 8 7.7909 8 10C8 12.2091 9.7909 14 12 14C14.2091 14 16 12.2091 16 10ZM14 10C14 11.1046 13.1046 12 12 12C10.8954 12 10 11.1046 10 10C10 8.8954 10.8954 8 12 8C13.1046 8 14 8.8954 14 10Z");
  stroke: none;
}

</style>
