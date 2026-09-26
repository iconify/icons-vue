<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gz6xjjb1q"/><path class="mkufoju3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-arrow-in-right-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gz6xjjb1q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 5L2 19C2 19.5523 2.44772 20 3 20L13 20L13 11L22 11L22 5C22 4.44772 21.5523 4 21 4L3 4C2.44772 4 2 4.44772 2 5ZM13.5 8.5C13.5 9.3284 12.8284 10 12 10C11.1716 10 10.5 9.3284 10.5 8.5C10.5 7.6716 11.1716 7 12 7C12.8284 7 13.5 7.6716 13.5 8.5Z");
  stroke: none;
}

.mkufoju3m {
  d: path("M22 11L22 4L2 4L2 20L13 20M15 17L22 17M18.7071 20.2929L22 17L18.7071 13.7071");
}

</style>
