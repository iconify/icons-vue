<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rw2t5c44l"/><path class="ksir6-k7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:travel-business-trip" /></template>
<style>
.ksir6-k7v {
  d: path("M6 9.5h5V13H6ZM4.25 19.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm7.973-1.02q-.159-.112-.344-.171T11.5 18.5q-.061 0-.123.006q-.061.006-.121.018t-.119.03t-.115.041t-.111.053t-.105.063q-.052.034-.099.073t-.091.082q-.043.044-.082.091t-.073.099q-.034.051-.063.105t-.053.111t-.041.115t-.03.119t-.018.121q-.006.062-.006.123t.006.123q.006.061.018.121t.03.119t.041.115q.024.057.053.111t.063.105t.073.099t.082.091q.044.043.091.082t.099.073t.105.063t.111.053q.056.023.115.041t.119.03t.121.018t.123.006q.353 0 .654-.185M18.5 15c.75 0 .75 1 .75 1.5v1L22 19.25V20l-2.75-.75v1.5l1 .75v.5l-1.75-.5l-1.75.5v-.5l1-.75v-1.5L15 20v-.75l2.75-1.75v-1c0-.5 0-1.5.75-1.5Z");
}

.rw2t5c44l {
  d: path("M12.2 18.5H3v-13h11v11.1M6.5 5.5v-3h4v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
