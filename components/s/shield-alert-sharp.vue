<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qpod6tb2n"/><path clip-rule="evenodd" class="m6hdizbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-alert-sharp" /></template>
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

.qpod6tb2n {
  d: path("M12 6V14M20 5.309V15.778L18.612 17.573C17.41 19.128 15.503 20.87 12.83 21.853C12.294 22.049 11.706 22.049 11.17 21.853C8.497 20.87 6.59 19.128 5.388 17.573L4 15.778V5.309L5.182 5.168C7.83 4.854 9.83 3.532 11.024 2.373C11.537 1.876 12.463 1.876 12.976 2.373C14.17 3.532 16.17 4.854 18.817 5.168L20 5.309Z");
}

</style>
