<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mbe0j7bcs"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-off-sharp-fill" /></template>
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

.mbe0j7bcs {
  fill: currentColor;
  d: path("M21.7071 21.7071C21.5196 21.8946 21.2652 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.7348 2.1054 2.4804 2.2929 2.2929L7.9627 7.9627L7.9627 16.6987C7.9627 17.251 8.4104 17.6987 8.9627 17.6987C9.1501 17.6987 9.3338 17.646 9.4927 17.5467L14.449 14.449ZM5.6569 2L21 2C21.5523 2 22 2.4477 22 3L22 18.3431Z");
  stroke: none;
}

</style>
