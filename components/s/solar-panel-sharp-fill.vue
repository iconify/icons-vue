<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="utpis-b9n"/><path class="d8j5o4bhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-panel-sharp-fill" /></template>
<style>
.d8j5o4bhh {
  d: path("M12 15L12 21M7 21L17 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.utpis-b9n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.0513 2.6838C5.1874 2.2754 5.5696 2 6 2L18 2C18.4304 2 18.8126 2.2754 18.9487 2.6838L22.9487 14.6838C22.9827 14.7857 23 14.8925 23 15C23 15.5523 22.5523 16 22 16L2 16C1.4477 16 1 15.5523 1 15C1 14.8925 1.0173 14.7857 1.0513 14.6838ZM8.8827 4L8.4383 8L5.3874 8L4.7208 10L8.2161 10L7.7717 14L9.7839 14L10.2284 10L13.7716 10L14.2161 14L16.2283 14L15.7839 10L19.2792 10L18.6126 8L15.5617 8L15.1173 4L13.105 4L13.5494 8L10.4506 8L10.895 4Z");
  stroke: none;
}

</style>
