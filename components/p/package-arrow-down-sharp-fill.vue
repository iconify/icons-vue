<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k1ypc5qnl"/><path class="rpezfdbzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-down-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k1ypc5qnl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 6.8477L22 13L16 13L13 13L13 22L12 22L2 17.1523L2 6.8477L12 12L22 6.8477Z");
  stroke: none;
}

.rpezfdbzz {
  d: path("M2 6.8477L12 12M12 12L22 6.8477M7 4.4239L17 9.4239M12 12L12 22L2 17.1523L2 6.8477L12 2L22 6.8477L22 13M19 15L19 22M15.7071 18.7071L19 22L22.2929 18.7071");
}

</style>
