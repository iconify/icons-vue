<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yyqv39wxs"/><path class="pusvzil9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-right-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pusvzil9n {
  d: path("M15.5381 4.5L20.7543 9.34362C21.5484 10.081 21.9996 11.1158 21.9996 12.1994C21.9996 13.3418 21.4984 14.4266 20.6285 15.1671L15.5381 19.5");
}

.yyqv39wxs {
  stroke-linejoin: round;
  d: path("M6.0001 10.1308C7.61344 8.97671 9.45473 8.57075 11 8.57075V6.22616C11 5.26817 11 4.78917 11.2952 4.65662C11.5903 4.52407 11.9484 4.8423 12.6644 5.47875L16.6367 9.00968C18.2053 10.404 18.9896 11.1012 18.9896 11.9993C18.9896 12.8975 18.2053 13.5946 16.6367 14.989L12.6644 18.5199C11.9484 19.1563 11.5903 19.4746 11.2952 19.342C11 19.2095 11 18.7305 11 17.7725V15.4279C7.4 15.4279 3.5 17.1422 2 19.9993C2 17.5676 2.37726 15.621 3.0001 14.0735");
}

</style>
