<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bby1cj_ck"/><path class="x0m_7lm5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spreadsheet-formula" /></template>
<style>
.bby1cj_ck {
  d: path("M10.9 20.5H2.5v-17h19v10.3m-19-5.3h19M9 8.5v12m-6.5-6h10.1m7.5 0h.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x0m_7lm5l {
  d: path("M14.75 21.75V17a2 2 0 0 1 2-2h.5m-3.5 2.75H16m2.25 0l3.5 4m0-4l-3.5 4");
}

</style>
