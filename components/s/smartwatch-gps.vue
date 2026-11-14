<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozyd--bty"/><path class="cm56ntb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartwatch-gps" /></template>
<style>
.cm56ntb6t {
  d: path("M12 15s-3-2.5-3-4.75a3 3 0 0 1 6 0C15 12.5 12 15 12 15Z");
}

.ozyd--bty {
  d: path("M7 6h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm1.5 0L9 3h6l.5 3m-7 12l.5 3h6l.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
