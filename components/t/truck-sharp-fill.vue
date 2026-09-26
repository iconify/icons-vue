<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p4w_3pf-h"/><path class="lmypq5bjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lmypq5bjt {
  d: path("M14 18L14 4L2 4L2 18L5 18M9 18L14 18M19 18L22 18L22 12.1716L17.8284 8L14 8M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.p4w_3pf-h {
  fill: currentColor;
  d: path("M5 18L3 18C2.4477 18 2 17.5523 2 17L2 5C2 4.4477 2.4477 4 3 4L13 4C13.5523 4 14 4.4477 14 5L14 18L9 18C9 16.8954 8.1046 16 7 16C5.8954 16 5 16.8954 5 18Z");
  stroke: none;
}

</style>
