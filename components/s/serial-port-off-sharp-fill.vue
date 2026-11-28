<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="eb7_p5ogc"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.eb7_p5ogc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 19L4.159 19C3.675 19 3.2604 18.6533 3.1748 18.177L1.0173 6.177C1.0068 6.1186 1.0015 6.0593 1.0015 6C1.0015 5.4477 1.4492 5 2.0015 5L5 5ZM8.6569 5L12 5L21.9985 5C22.5508 5 22.9985 5.4477 22.9985 6C22.9985 6.0593 22.9932 6.1186 22.9827 6.177L20.9789 17.322ZM17 10C17 9.4477 16.5523 9 16 9C15.4477 9 15 9.4477 15 10C15 10.5523 15.4477 11 16 11C16.5523 11 17 10.5523 17 10Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
