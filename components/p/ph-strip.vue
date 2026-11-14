<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tf_s6-bhv"/><path class="gr_b0xyxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ph-strip" /></template>
<style>
.gr_b0xyxq {
  d: path("m12.686 2.268l3.759 1.368l-5.131 14.096l-3.759-1.368Zm-2.309 6.343l3.759 1.368m-4.699 1.216l3.758 1.368m-4.699 1.216l3.759 1.369");
}

.tf_s6-bhv {
  d: path("M5 10v9a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19v-9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
