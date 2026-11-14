<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="px1gu3yub"/><path class="pctqrl3gt"/><path class="ud2s7b0nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:migration-flow" /></template>
<style>
.pctqrl3gt {
  d: path("m18.5 9.25l2 1.25l1.25-2m-1.25 5c-1.5 7-15.5 7-17 0");
}

.px1gu3yub {
  d: path("M3.5 10.5c1.5-7 15.5-7 17 0");
}

.ud2s7b0nb {
  d: path("m2.25 15.5l1.25-2l2 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
