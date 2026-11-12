<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p63g3mbxh"/><path class="lqdncdb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqdncdb1y {
  d: path("M14.1211 8.04928H18.3637L18.3637 3.80664");
}

.p63g3mbxh {
  d: path("M18.3637 8.05025L17.6566 7.34315C14.5324 4.21895 9.4671 4.21895 6.3429 7.34315C3.21871 10.4673 3.21871 15.5327 6.3429 18.6569C9.4671 21.781 14.5324 21.781 17.6566 18.6569C19.4734 16.84 20.2337 14.3668 19.9374 12.0005");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
