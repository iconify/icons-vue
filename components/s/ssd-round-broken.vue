<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vpq758wsx"/><path class="zobtaob_b"/><path class="a6h11icdc"/><path class="pts2-acil"/><path class="jkpkp9brv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-round-broken" /></template>
<style>
.a6h11icdc {
  d: path("M15.5 17V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkpkp9brv {
  d: path("M10.5 17V18");
}

.pts2-acil {
  d: path("M13 17V18");
}

.vpq758wsx {
  d: path("M21.5534 15.4813C20.9538 14.3515 19.8111 13.5882 18.5 13.5882H5.5C4.18893 13.5882 3.04623 14.3515 2.44664 15.4813M21.5534 15.4813C21.8378 16.0172 22 16.6356 22 17.2941C22 19.3408 20.433 21 18.5 21H12M21.5534 15.4813L20.2767 10.2995M2.44664 15.4813L5 5.11765C5.5 3.52941 6.39543 3 7.5 3H16.5C17.6046 3 18.5 3.52941 19 5.11765L19.3192 6.4131M2.44664 15.4813C2.16221 16.0172 2 16.6356 2 17.2941C2 19.3408 3.567 21 5.5 21H8");
}

.zobtaob_b {
  d: path("M18 17V18");
}

</style>
