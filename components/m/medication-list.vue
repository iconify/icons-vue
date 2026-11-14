<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l-8_qo57v"/><path class="ij_tnfben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medication-list" /></template>
<style>
.ij_tnfben {
  d: path("M15.5 16h5v5.75h-5Z");
}

.l-8_qo57v {
  d: path("M12.7 19H3V2.5h13v8.7M6 7h7m-7 3.5h7M6 14h4.5m4.5 0h6v2h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
