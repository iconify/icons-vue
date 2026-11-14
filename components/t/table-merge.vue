<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4cv4tbfu"/><path class="h2i0s9bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-merge" /></template>
<style>
.h2i0s9bav {
  d: path("M5.5 15H10m-2-2l2 2l-2 2m10.5-2H14m2-2l-2 2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4cv4tbfu {
  d: path("M2.5 3.5h19v17h-19Zm0 5.5h19M12 3.5V9");
}

</style>
