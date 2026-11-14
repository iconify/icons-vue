<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="whcxf3shl"/><path class="egvzcai4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-owed" /></template>
<style>
.egvzcai4f {
  d: path("M6 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whcxf3shl {
  d: path("M15.2 21.5H3.5v-19H17v9.2M7 15.5l7-8");
}

</style>
