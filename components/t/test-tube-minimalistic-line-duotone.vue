<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sjd77kgpz"/><path class="aw1-40b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-minimalistic-line-duotone" /></template>
<style>
.aw1-40b2a {
  d: path("M6.80078 11.7834L8.075 11.9257C9.0977 12.0398 9.90504 12.8507 10.0187 13.8779C10.1062 14.6689 10.6104 15.3515 11.3386 15.665L13 16.3547");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sjd77kgpz {
  d: path("M21 9.84867L20.2387 9.08398M20.2387 9.08398L14.8635 3.68504M20.2387 9.08398L13 16.3547L9.48838 19.8818C8.00407 21.3727 5.59754 21.3727 4.11323 19.8818C2.62892 18.391 2.62892 15.9738 4.11323 14.4829L14.8635 3.68504M14.8635 3.68504L14.1815 3");
}

</style>
