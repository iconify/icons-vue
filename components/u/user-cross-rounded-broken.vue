<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="b9iws8suz"/><path class="yez-gzbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-cross-rounded-broken" /></template>
<style>
.b9iws8suz {
  d: path("M20 17.5L19 18.5M19 18.5L18 19.5M19 18.5L18 17.5M19 18.5L20 19.5");
}

.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yez-gzbul {
  d: path("M15.5841 20.4366C14.5358 20.7944 13.3099 21 12 21C8.13401 21 5 19.2091 5 17C5 15.6407 6.18652 14.4398 8 13.717M12 13C14.6083 13 16.8834 13.8152 18.0877 15.024");
}

</style>
