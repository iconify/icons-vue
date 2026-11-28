<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x6ktbqh6x"/><path class="kvrq4etcm"/><path clip-rule="evenodd" class="cvyefvb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-info-sharp-two-tone" /></template>
<style>
.cvyefvb3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7C13 7.552 12.552 8 12 8C11.448 8 11 7.552 11 7C11 6.448 11.448 6 12 6C12.552 6 13 6.448 13 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kvrq4etcm {
  d: path("M12 18V10M20 5.309V15.778L18.612 17.573C17.41 19.128 15.503 20.87 12.83 21.853C12.294 22.049 11.706 22.049 11.17 21.853C8.497 20.87 6.59 19.128 5.388 17.573L4 15.778V5.309L5.182 5.168C7.83 4.854 9.83 3.532 11.024 2.373C11.537 1.876 12.463 1.876 12.976 2.373C14.17 3.532 16.17 4.854 18.817 5.168L20 5.309Z");
}

.x6ktbqh6x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 5.309V15.778C21 15.999 20.927 16.215 20.791 16.39L19.403 18.185C18.148 19.808 16.033 21.741 13.175 22.791C12.472 23.049 11.528 23.049 10.825 22.791C7.967 21.741 5.852 19.808 4.597 18.185L3.209 16.39C3.073 16.214 3 15.999 3 15.778V5.309C3 4.802 3.379 4.376 3.882 4.316L5.065 4.175C7.477 3.889 9.2 2.75 10.328 1.655C11.132 0.876 12.868 0.876 13.672 1.655C14.8 2.75 16.523 3.889 18.935 4.175L20.118 4.316C20.621 4.376 21 4.802 21 5.309Z");
  stroke: none;
}

</style>
