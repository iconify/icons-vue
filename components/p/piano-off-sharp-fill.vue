<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="cp57lkbzh"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.cp57lkbzh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 6L6 13C6.5523 13 7 13.4477 7 14L7 20C7 20.5523 6.5523 21 6 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3L3 3ZM21 21L10 21C9.4477 21 9 20.5523 9 20L9 14C9 13.4477 9.4477 13 10 13L10 10ZM6.6569 3L12 3L22 3C22.5523 3 23 3.4477 23 4L23 19.3431L16.6569 13L18 13L18 5L14 5L14 10.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
