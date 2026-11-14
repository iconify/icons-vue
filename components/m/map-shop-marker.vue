<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xnfkppc2r"/><path class="gns-czbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-shop-marker" /></template>
<style>
.gns-czbtr {
  d: path("m8.5 8.5l1-3h5l1 3Zm1 0V13h5V8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xnfkppc2r {
  d: path("M12 21.5c-3-3-7.5-7.5-7.5-12a7.5 7.5 0 0 1 15 0c0 4.5-4.5 9-7.5 12");
}

</style>
