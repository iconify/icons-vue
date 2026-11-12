<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cihr55ejt"/><path class="sdb9eeb1p"/><path class="bkpaj_wfp"/><path class="pf95emypg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-angle-linear" /></template>
<style>
.bkpaj_wfp {
  d: path("M7.5 22C9.98528 22 12 17.5228 12 12C12 6.47715 9.98528 2 7.5 2M7.5 22C5.01472 22 3 17.5228 3 12C3 6.47715 5.01472 2 7.5 2M7.5 22H16.5C18.9853 22 21 17.5228 21 12C21 6.47715 18.9853 2 16.5 2H7.5");
}

.cihr55ejt {
  d: path("M7.5 22C9.98528 22 12 17.5228 12 12C12 6.47715 9.98528 2 7.5 2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pf95emypg {
  d: path("M9 12H8");
}

.sdb9eeb1p {
  d: path("M9 12C9 15.3137 8.32843 18 7.5 18C6.67157 18 6 15.3137 6 12C6 8.68629 6.67157 6 7.5 6C8.32843 6 9 8.68629 9 12Z");
}

</style>
