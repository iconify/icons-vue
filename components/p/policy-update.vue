<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o9wz3_f2o"/><path class="j6zf5sbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-update" /></template>
<style>
.j6zf5sbps {
  d: path("M13.75 14.25L15 15.5l1.25-1.75");
}

.o9wz3_f2o {
  d: path("M10.7 19.5H3v-17h13v7.6M6 7h7m-7 3.5h7M6 14h4m9-.464A4 4 0 1 1 13.536 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
