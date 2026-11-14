<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lv68kwbyp"/><path class="gns-czbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-shop-marker" /></template>
<style>
.gns-czbtr {
  d: path("m8.5 8.5l1-3h5l1 3Zm1 0V13h5V8.5");
}

.lv68kwbyp {
  d: path("M12 21.5c-3-3-7.5-7.5-7.5-12a7.5 7.5 0 0 1 15 0c0 4.5-4.5 9-7.5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
