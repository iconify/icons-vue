<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="u95i762fe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-3d-scan" /></template>
<style>
.dxsxh5xhc {
  d: path("M6 2.5h12v19H6Z");
}

.u95i762fe {
  d: path("m12 9.5l2.25 1.25v2.5L12 14.5l-2.25-1.25v-2.5Zm-2.25 1.25L12 12l2.25-1.25M12 12v2.5M8.75 8V6h1.75m3 0h1.75v2m-6.5 8v2h1.75m3 0h1.75v-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
