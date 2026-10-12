<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx2lszbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:surgical-face-mask-sharp" /></template>
<style>
.tx2lszbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 6.75c3.25-1 6.25-1 9.5 0v10c-3.25 1.75-6.25 1.75-9.5 0ZM9.5 10h5m-5 3.5h5M7.25 7.75L3 3.25m13.75 4.5L21 3.25M7.25 15.75l-4.25 5m13.75-5l4.25 5");
}

</style>
