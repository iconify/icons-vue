<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yzaa0w5oy"/><path class="r9g1c9bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-all-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r9g1c9bux {
  d: path("M8.2929 3.7071L2 10L8.2929 16.2929");
}

.yzaa0w5oy {
  stroke-opacity: 0.4;
  d: path("M14.2929 3.7071L8 10L14.2929 16.2929M8 10L22 10L22 21");
}

</style>
