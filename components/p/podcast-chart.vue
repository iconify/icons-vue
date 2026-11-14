<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tsv_l2qla"/><path class="n60-vhb8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-chart" /></template>
<style>
.n60-vhb8i {
  d: path("M9.172 8.828a4 4 0 1 1 5.656 0");
}

.tsv_l2qla {
  d: path("M2.5 21v-5.5H8v-3.75h8v5.75h5.5V21Zm8.25-15a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
