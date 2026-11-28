<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z4tq2dbma"/><path class="fe57rpb_k"/><path clip-rule="evenodd" class="cvyefvb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-info-sharp-duotone" /></template>
<style>
.cvyefvb3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7C13 7.552 12.552 8 12 8C11.448 8 11 7.552 11 7C11 6.448 11.448 6 12 6C12.552 6 13 6.448 13 7Z");
  stroke: none;
}

.fe57rpb_k {
  d: path("M12 18V10");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z4tq2dbma {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 10.543V15.778C21 15.999 20.927 16.215 20.791 16.39L19.403 18.185C18.114 19.851 16.064 21.73 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.936 21.73 5.885 19.851 4.597 18.185L3.209 16.389C3.073 16.214 3 15.999 3 15.778V5.309C3 4.802 3.379 4.376 3.882 4.316L5.065 4.175C7.443 3.893 9.248 2.703 10.328 1.655C11.229 0.782 12.771 0.782 13.672 1.655C14.752 2.703 16.557 3.893 18.935 4.175L20.118 4.316C20.621 4.376 21 4.802 21 5.309V10.543Z");
  stroke: none;
}

</style>
