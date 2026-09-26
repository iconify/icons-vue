<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q6b_7xb6g"/><path class="wwyljr91l"/><path class="wz_ohib0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-remove-after-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6b_7xb6g {
  stroke-opacity: 0.4;
  d: path("M20 6L20 3L11 3M11 21L20 21L20 18");
}

.wwyljr91l {
  fill: currentColor;
  d: path("M12 2L12 22L2 22C1.4477 22 1 21.5523 1 21L1 3C1 2.4477 1.4477 2 2 2L12 2Z");
  stroke: none;
}

.wz_ohib0s {
  d: path("M15.7071 8.7071L22.2929 15.2929M22.2929 8.7071L15.7071 15.2929");
}

</style>
