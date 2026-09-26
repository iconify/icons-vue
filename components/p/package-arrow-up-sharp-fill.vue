<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k1ypc5qnl"/><path class="k-de5lb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-up-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k-de5lb4p {
  d: path("M2 6.8477L12 12M12 12L22 6.8477M7 4.4239L17 9.4239M12 12L12 22L2 17.1523L2 6.8477L12 2L22 6.8477L22 13M19 23L19 16M15.7071 19.2929L19 16L22.2929 19.2929");
}

.k1ypc5qnl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 6.8477L22 13L16 13L13 13L13 22L12 22L2 17.1523L2 6.8477L12 12L22 6.8477Z");
  stroke: none;
}

</style>
