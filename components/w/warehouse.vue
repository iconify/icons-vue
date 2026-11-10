<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg9p9tbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:warehouse" /></template>
<style>
.lg9p9tbtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 22H20C21.1046 22 22 21.1 22 20V9C22 8.39 21.6359 7.85 21.0769 7.62L12.7692 2.15C12.5255 2.05 12.2641 2 12 2C11.7359 2 11.4745 2.05 11.2308 2.15L2.9231 7.62C2.3641 7.85 2 8.39 2 9V20C2 21.1 2.8954 22 4 22H6M18 22H6M18 22V18M6 22V18M18 18H6M18 18V14M6 18V14M6 14V12C6 10.9 6.8954 10 8 10H16C17.1046 10 18 10.9 18 12V14M6 14H18");
}

</style>
