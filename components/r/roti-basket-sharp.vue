<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ned9cubgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roti-basket-sharp" /></template>
<style>
.ned9cubgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.75c0-3 3-5 6.5-5s6.5 2 6.5 5Zm-2.5 0h18l-1.6 7.75l-.212 1.473L17.7 21H6.3l-1.488-.027L4.6 19.5Zm.75 3h16.5M4.25 18h15.5");
}

</style>
