<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k4f9t_brm"/><path class="mmun5z68z"/><path class="hgwpgxsau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-add-above-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hgwpgxsau {
  d: path("M12 1L12 9M8 5L16 5");
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

</style>
