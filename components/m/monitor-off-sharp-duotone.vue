<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eym7bl_re"/><path class="tay61hbyz"/><path class="f4vx4ccga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-off-sharp-duotone" /></template>
<style>
.eym7bl_re {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 17H13V19H17V21H7V19H11V17H2C1.4477 17 1 16.5523 1 16V4C1 3.4477 1.4477 3 2 3H3L17 17Z");
  stroke: none;
}

.f4vx4ccga {
  d: path("M1.70715 1.70703L22.293 22.2928");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tay61hbyz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.6569 3L22 3C22.5523 3 23 3.4477 23 4L23 16C23 16.5523 22.5523 17 22 17L20.6569 17Z");
  stroke: none;
}

</style>
