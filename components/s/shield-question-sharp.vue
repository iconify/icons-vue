<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vhrxojizq"/><path clip-rule="evenodd" class="g1gyir_9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-question-sharp" /></template>
<style>
.g1gyir_9g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 17.5C13 18.052 12.552 18.5 12 18.5C11.448 18.5 11 18.052 11 17.5C11 16.948 11.448 16.5 12 16.5C12.552 16.5 13 16.948 13 17.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vhrxojizq {
  d: path("M9.6 10.9V9.9C9.6 8.574 10.674 7.5 12 7.5C13.326 7.5 14.4 8.574 14.4 9.9C14.4 10.869 13.817 11.743 12.923 12.115C12.364 12.348 12 12.894 12 13.5V14.5M20 5.309V15.778L18.612 17.573C17.41 19.128 15.503 20.87 12.83 21.852C12.294 22.049 11.706 22.049 11.17 21.852C8.497 20.87 6.59 19.128 5.388 17.573L4 15.778V5.309L5.182 5.168C7.83 4.854 9.83 3.532 11.024 2.373C11.537 1.876 12.463 1.876 12.976 2.373C14.17 3.532 16.17 4.854 18.817 5.168L20 5.309Z");
}

</style>
