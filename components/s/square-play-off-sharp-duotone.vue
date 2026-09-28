<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eeudo8b0b"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.eeudo8b0b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.7071 21.7071C21.5196 21.8946 21.2652 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.7348 2.1054 2.4804 2.2929 2.2929L8.9627 8.9627L7.9627 8.9627L7.9627 16.6987C7.9627 17.251 8.4104 17.6987 8.9627 17.6987C9.1501 17.6987 9.3338 17.646 9.4927 17.5467L14.2533 14.5713L13.7233 13.7233ZM9.9627 9.9627L9.9627 14.8945L12.9976 12.9976ZM5.6569 2L21 2C21.5523 2 22 2.4477 22 3L22 18.3431Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
