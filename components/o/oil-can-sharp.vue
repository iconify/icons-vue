<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfo33k5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-can-sharp" /></template>
<style>
.bfo33k5pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 20.25V16a5.25 5.25 0 0 1 10.5 0v5.25H3.25zm8.5-8.25L19 4.75M3.25 17h10.5M20 7.5l1.25 1.667V10a1.25 1.25 0 0 1-2.5 0v-.833z");
}

</style>
