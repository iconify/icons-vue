<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jbz4_mzqr"/><path class="tyv5mcb3q"/><path class="n6_kje8jt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-mark-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbz4_mzqr {
  d: path("M8 6.2969C8 3.92379 9.95877 2 12.375 2");
}

.n6_kje8jt {
  stroke-linejoin: round;
  d: path("M13 22H13.0001");
}

.tyv5mcb3q {
  d: path("M12.375 15.7501V12.8855C12.375 11.6198 13.4904 10.6422 14.5995 9.99769C15.8868 9.2497 16.75 7.87231 16.75 6.2969C16.75 5.22875 16.3532 4.25163 15.6964 3.5");
}

</style>
