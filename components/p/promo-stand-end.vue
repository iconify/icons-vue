<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ik4vt6b2h"/><path class="zd52f8bbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:promo-stand-end" /></template>
<style>
.ik4vt6b2h {
  d: path("M3 2.5h18v5H3Zm1.5 5v14m15-14v14m-17 0h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd52f8bbt {
  d: path("M5.5 3.75v2.5L9.5 5ZM11 5h7M4.5 14.5h15M7 14.5v-3l1-1v-1m2 0v1l1 1v3m2.5-4h4v4h-4Zm-6.5 7h4v4H7Zm6 .5h5v3.5h-5Z");
}

</style>
