<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a0xvf11wd"/><path class="pvoaf2dku"/><path class="c16dwgb5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-certificate" /></template>
<style>
.a0xvf11wd {
  d: path("M12.6 18H2.5V3h19v8.9");
}

.c16dwgb5g {
  d: path("M16.25 18.25v3.25l1.5-1l1.5 1v-3.25");
}

.pvoaf2dku {
  d: path("M12.3 15H5.5V6h13v4.5M15 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
