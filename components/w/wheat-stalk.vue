<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lhap_ib-m"/><path class="t4yl7ubws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheat-stalk" /></template>
<style>
.lhap_ib-m {
  d: path("M12 6.5v15m0-15c-1.25-1.5-1.25-2.5 0-4c1.25 1.5 1.25 2.5 0 4Z");
}

.t4yl7ubws {
  d: path("M12 8.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0 6.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0-3.25c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4Zm0 6.5c2.5 0 4-1.5 4-4c-2.5 0-4 1.5-4 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
