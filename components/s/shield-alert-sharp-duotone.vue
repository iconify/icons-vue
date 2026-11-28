<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w-_avwbgq"/><path class="t-zekuxad"/><path clip-rule="evenodd" class="m6hdizbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-alert-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m6hdizbcy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 17C13 17.552 12.552 18 12 18C11.448 18 11 17.552 11 17C11 16.448 11.448 16 12 16C12.552 16 13 16.448 13 17Z");
  stroke: none;
}

.t-zekuxad {
  d: path("M12 6V14");
}

.w-_avwbgq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 5.309V15.778C21 15.999 20.927 16.215 20.791 16.39L19.403 18.185C18.148 19.808 16.033 21.741 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.967 21.741 5.852 19.808 4.597 18.185L3.209 16.39C3.073 16.214 3 15.999 3 15.778V5.309C3 4.802 3.379 4.376 3.882 4.316L5.065 4.175C7.477 3.889 9.2 2.75 10.328 1.655C11.229 0.782 12.771 0.782 13.672 1.655C14.8 2.75 16.523 3.889 18.935 4.175L20.118 4.316C20.621 4.376 21 4.802 21 5.309Z");
  stroke: none;
}

</style>
