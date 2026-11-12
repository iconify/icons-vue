<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iyh26i1-m"/><path class="y7wqo0bjz"/><path class="y7ce83b9a"/><path class="ac1l4pbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-rotate-angle-line-duotone" /></template>
<style>
.ac1l4pbcd {
  d: path("M5.50174 17C5.5 16.6878 5.5 16.355 5.5 16V8C5.5 5.17157 5.5 3.75736 6.37868 2.87868C7.25736 2 8.67157 2 11.5 2H12.5C15.3284 2 16.7426 2 17.6213 2.87868C18.5 3.75736 18.5 5.17157 18.5 8V16C18.5 16.355 18.5 16.6878 18.4983 17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyh26i1-m {
  d: path("M15 5H9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y7ce83b9a {
  d: path("M20.9605 15C21.6259 15.5272 22 16.1214 22 16.75C22 18.5847 18.8131 20.1263 14.5 20.5635");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y7wqo0bjz {
  stroke-linejoin: round;
  d: path("M10.5 20.6435V22L12 20.6875L10.5 19.375V20.6435ZM10.5 20.6435C5.68874 20.3585 2 18.7239 2 16.75C2 16.1214 2.37412 15.5272 3.03947 15");
}

</style>
