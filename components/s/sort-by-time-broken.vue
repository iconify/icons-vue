<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vkwwp42am"/><path class="bw4rmmbty"/><path class="nyyahnbxx"/><circle class="byu9zgdxu"/><path class="eonjggvry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-by-time-broken" /></template>
<style>
.bw4rmmbty {
  d: path("M8 12H2");
}

.byu9zgdxu {
  cx: 17px;
  cy: 12px;
  r: 5px;
}

.eonjggvry {
  stroke-linejoin: round;
  d: path("M17 10V11.8462L18 13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyyahnbxx {
  d: path("M10 17H2");
}

.vkwwp42am {
  d: path("M10 7L2 7");
}

</style>
