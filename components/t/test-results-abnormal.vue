<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4doy9bxq"/><path class="yxttrebrc"/><path class="a2vftxo8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-results-abnormal" /></template>
<style>
.a2vftxo8q {
  d: path("M19 3.5V10m-2.25-2.25L19 10l2.25-2.25m-7-4.25v3m0 2.5h.01");
}

.d4doy9bxq {
  d: path("M2.5 13h19v4.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yxttrebrc {
  fill: currentColor;
  d: path("M7.5 13h7v4.5h-7Z");
}

</style>
