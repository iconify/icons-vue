<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k4f9t_brm"/><path class="mmun5z68z"/><path class="yd11afbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-remove-above-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k4f9t_brm {
  stroke-opacity: 0.4;
  d: path("M6 4L3 4L3 13M21 13L21 4L18 4");
}

.mmun5z68z {
  fill: currentColor;
  d: path("M2 12L22 12L22 22C22 22.5523 21.5523 23 21 23L3 23C2.4477 23 2 22.5523 2 22L2 12Z");
  stroke: none;
}

.yd11afbgt {
  d: path("M8.7071 1.7071L15.2929 8.2929M15.2929 1.7071L8.7071 8.2929");
}

</style>
